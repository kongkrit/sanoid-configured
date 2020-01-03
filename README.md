# sanoid-configured
configured sanoid (https://github.com/jimsalterjrs/sanoid), ready to apt install on Ubuntu 18.04 LTS

## installation
* `unzip sanoid(version).zip`
* become root `sudo -i`
* `cd sanoid`
* `apt install --yes ../sanoid_*_all.deb`
* add `/etc/sanoid/sanoid.conf` - tweak as needed
* `sudo contab -e`  and add  `* * * * * /usr/sbin/sanoid --cron`
