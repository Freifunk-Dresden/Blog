---
layout: post
title: Release Server Firmware 1.6.2
author: Sven Kinne
category:
- News
- Firmware
---

Ein neues **stable Update** für unsere Gateway Server ([ffdd-server](https://github.com/Freifunk-Dresden/ffdd-server)) - [Firmware Version 1.6.2](https://github.com/Freifunk-Dresden/ffdd-server/releases/tag/T_RELEASE_v1.6.2) ist veröffentlicht.

Dieses Release enthält unter anderem einen fix für **Debian 11 (bullseye)**. Einige Packages die für 'saltstack' benötigten werden fehlen bei der Installation und müssen manuell nachinstalliert werden.  
Hierbei handelt es sich um: `python3-yaml`, `python3-msgpack`, `python3-distro`, `python3-tornado`, `python3-looseversion`, `python3-packaging` und `python3-jinja2`.  
Das Problem scheint mit der Umstellung zu dem neuen salt-repo in Version [T_RELEASE_v1.5.1rc1](https://github.com/Freifunk-Dresden/ffdd-server/releases/tag/T_RELEASE_v1.5.1rc1) zusammenzuhängen.  
(Neue ffdd-server Installationen mit Debian 11 und alle anderen Versionen scheinen von dem Problem nicht betroffen zu sein.)

Um deine Debian 11 Installation zu fixen müssen die oben genannten Packages wiefolgt installiert werden:  
`apt -y install python3-yaml python3-msgpack python3-distro python3-tornado python3-looseversion python3-packaging python3-jinja2`.  
Nach der Installation der Packages sollte `freifunk-call` wieder wie gewohnt funktionieren.

Änderungen im Überblick seit dem letzten Release 1.6.0 (enthält auch die Änderungen aus Version 1.6.1):

- fix debian 11 installation
- add config option to disable the speedtest plugin
- update digitalcourage dns forwarder
- update bind (dns) zonefiles
- revision/optimization of some scripts
- some smaller changes


**Full Changelog**: [https://github.com/Freifunk-Dresden/ffdd-server/compare/T_RELEASE_v1.6.0...T_RELEASE_v1.6.2](https://github.com/Freifunk-Dresden/ffdd-server/compare/T_RELEASE_v1.6.0...T_RELEASE_v1.6.2)

Alle Änderungen im Überblick findet ihr im [CHANGELOG](https://github.com/Freifunk-Dresden/ffdd-server/blob/T_RELEASE_v1.6.2/CHANGELOG.md).
