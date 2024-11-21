---
layout: post
title: Release Server Firmware 1.6.0
author: Sven Kinne
category:
- News
- Firmware
---

Ein neues **stable Update** für unsere Gateway Server ([ffdd-server](https://github.com/Freifunk-Dresden/ffdd-server)) - [Firmware Version 1.6.0](https://github.com/Freifunk-Dresden/ffdd-server/releases/tag/T_RELEASE_v1.6.0) ist veröffentlicht.

Dies enthält folgende Änderungen seit dem letzten Release 1.5.0:


	- add support for ubuntu 24.04 (LTS)
	- add speedtest web-ui tool
	- fix salt installation and change to new salt repo
	- install 'saltext-apache' extensions to replace deprecated 'apache' functionality in salt
	- add persistent keepalive for wireguard vpn gateway connections
	- update bind (dns) zonefiles
	- fix monitorix sources
	- show current 'commit' with freifunk version
	- show hostname on status page
	- cleanup unneeded stuff


**Full Changelog**: [https://github.com/Freifunk-Dresden/ffdd-server/compare/T\_RELEASE\_v1.5.0...T\_RELEASE\_v1.6.0](https://github.com/Freifunk-Dresden/ffdd-server/compare/T\_RELEASE\_v1.5.0...T\_RELEASE\_v1.6.0)

Alle Änderungen im Überblick findet ihr im [CHANGELOG](https://github.com/Freifunk-Dresden/ffdd-server/blob/T_RELEASE_v1.6.0/CHANGELOG.md).
