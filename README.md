# zabbix-check-dpkg

## Description

A script to monitor the status of the debian packaging system with [Zabbix](https://zabbix.com). (available updated and so on)

## Usage

* Clone this repo and build the debian package yourself with `LANG=C debuild -us -uc -b; dh clean`
**or**
* Install it directly from @istoph's [repository](https://blog.chr.istoph.de/repository/)
**or**
* Clone this repo and install the script and config by hand

## Licence

GPLv2 (see [debian/copyright](debian/copyright))

## Template for the Zabbix frontend

A template for the Zabbix frontend can be found, as usual in our packages, in [/usr/share/doc/${package_name}/](usr/share/doc/zabbix-check-dpkg/)
