---
layout: post
title: Release Server Firmware 1.5.0
author: Sven Kinne
category:
- News
- Firmware
---

Heute wurde ein neues Update für unsere Gateway [Server Firmware Version 1.5.0](https://github.com/Freifunk-Dresden/ffdd-server/releases/tag/T_RELEASE_v1.5.0) veröffentlicht.

Es sind einige Verbesserungen und Anpassungen vorgenommen worden um das Freifunk Netz in Dresden und deren Communities voranzutreiben.

Änderungen seit dem letzten Release 1.4.0:

- update bind (dns) zonefiles
- add vpn3le to ffl nodelist
- switch to new sysinfo.json version 18 that combines network statistics and makes it interface independent
- add config option to enable the firewall log
- remove support for debian 10
- add support for debian 12
- add tbb_wg and wg_vpn* traffic in sysinfo.json
- update build uci script
- cleanup some unneeded code snippets
- smaller fixes
- update [bmxd](https://github.com/Freifunk-Dresden/ffdd-bmxd) to version 1.4
- update [wireguard_accept_cgi](https://github.com/Freifunk-Dresden/wg_accept_cgi) to version 1.2.3
- update dns records for vpn gateways
- add locale gateway functionality
- fastd: allow to disable fastd via /etc/config/ffdd
- remove symlink of /etc/nvram.conf
- fix sudoers for iptables which is used by sysinfo.json to determine gw traffic (ovpn)
- fastd: add config to /etc/config/ffdd to disable fastd
- wireguard: sync wg registration (script) with the one used in firmware (to easier setting up connections between servers)
	- add "wg-backbone.sh register" cmd

Alle Änderungen im Überblick findet ihr im [CHANGELOG](https://github.com/Freifunk-Dresden/ffdd-server/blob/T_RELEASE_v1.5.0/CHANGELOG.md).
