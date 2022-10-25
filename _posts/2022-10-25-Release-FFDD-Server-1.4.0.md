---
layout: post
title: Release Server Firmware 1.4.0
author: Sven Kinne
category:
- News
- Firmware
---

Es gibt nach langer Zeit eine neue Server Firmware Version [1.4.0](https://github.com/Freifunk-Dresden/ffdd-server/releases/tag/T_RELEASE_v1.4.0).

Es sind einige Verbesserungen und Anpassungen vorgenommen worden um das Freifunk Netz in Dresden und deren Communities voranzutreiben.

Änderungen seit dem letzten Release 1.3.0:
	- removed support for debian 9 & ubuntu 16.04/18.04
	- add support for debian 11 & ubuntu 22.04
	- update fastd to version 22
	- update bmxd to version 1.2
	- update sysinfo.json
	- update internal dns
		- add zone for freifunk-leipzig (.ffl)
	- add ipip tunnel as alternative to bat0
	- add speedtest-backend
	- some bug fixes and optimizations

Alle Änderungen im Überblick findet ihr im [CHANGELOG](https://github.com/Freifunk-Dresden/ffdd-server/blob/T_RELEASE_v1.4.0/CHANGELOG.md).
