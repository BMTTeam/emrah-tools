jitsi-buster-installer
======================
`jitsi-buster-installer` installs a simple standalone Jitsi server. It's only
compatible with `Debian 10 Buster`. This script guides the user during the
installation to avoid potential problems.

See [Jitsi cluster
doc](https://github.com/emrahcom/emrah-buster-templates/blob/master/doc/jitsi_cluster.md)
if you need a scalable clustered Jitsi system.

## Usage
Run as `root`

```bash
wget -O jitsi-buster-installer https://raw.githubusercontent.com/emrahcom/emrah-tools/main/jitsi/installer/buster/jitsi-buster-installer

export JITSI_HOST=jitsi.mydomain.com
export TURN_HOST=turn.mydomain.com

bash jitsi-buster-installer
```