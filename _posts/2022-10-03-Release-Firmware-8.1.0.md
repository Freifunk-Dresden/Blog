---
layout: post
title: Release Firmware 8.1.0
author: Stephan Enderlein
category:
- News
- Firmware
---
Es gibt nach langer Zeit eine neue Release Version
[8.1.0](https://download.freifunk-dresden.de/firmware/8.1.0/).

Viele Verbesserungen und notwendige Anpassungen, um das Freifunk Netz in Dresden + Umgebung voranzutreiben, sind eingeflossen. Dabei mussten auch einige Anpassungen vorgenommen werden, die teilweise keine oder nur eingeschränkte Funktion von Router mit Firmware < 7.0.3 haben.

Es wird **dringend** empfohlen, auf die aktuelle Firmware [8.1.0](https://download.freifunk-dresden.de/firmware/8.1.0/) zu aktualisieren.

Änderungen seit der letzten Release 7.0.3:
- upgrade openwrt 19->21
- complete rework of internal network configuration to support DSA
- completely move from ad-hoc to 802.11s for meshing (more stable and more router support)
- add vlan meshing
- add wifi-roaming (light)
- add USB Tethering (for some routers with enough flash and memory)
- replace gateway tunnel (bmxd->ipip) to increase speed extremly
- rework communities (add support for "sub-communities" like Pirna)
- add new communities (Dresden, Nord-Ost, Nord-West, Sued-Ost, Sued-West, Pirna, Oberlausitz, Leipzig)
- add option to force ethernet port speed down to 100mbit/s
- add function to disable/enable backbone configuration in GUI
- add automatic port selection for bacckbone (info send by server)
- add better speedtest result display (gui)
- add colors to logs
- add option to control LEDs
- move wifi scan into background
- remove splash screen
- remove ddns
- add function to specifiy the time of nightly reboot or firmware auto update
- add minor firewall improvments (where backbone tunnels where created through freifunk network itself)
- bmxd (routing protocol deamon) improve switching from dead nodes to other
- improve loading speed for GUI
- sysinfo.json: add infos about wifi channel, wireguard.
- support more routers
