---
layout: post
title: Testing Firmware 8.2.2
author: Stephan Enderlein
category:
- News
- Firmware
---
Testing Firmware [8.2.2](https://download.freifunk-dresden.de/firmware/8.2.2/).

Diese Testing Firmware beinhaltet weitere Verbesserungen. Sie soll in Kürze in
eine neue Release führen.

Änderungen seit der letzten Release 8.2.0:
- WiFi: Für Router, wo genügend Speicher verfügbar ist, wurde WPA3 für den Client-Mode hinzugefügt
- Sysinfo: Umbau der Netzwerk-Statistik Sektion
- Firmware Upgrade: Firmware wurde für zukünftige Updates vorbereitet. Einige Router können direkt
  auf eine zukünftige Version aktualisert werden. Andere Router müssen zu erst auf diese 8.2.2
  wechseln, damit neuere Versionen akzeptiert werden. Grund ist openwrt.org, welche den Upgrade-Prozess
  nicht optimal eingebaut haben.
- Openvpn: Diese funktion wurde ausgebaut, da sie nicht verwendet wurde und der Datendurchsatz kaum nutzbar ist.
- Firewall: Es wurden weitere Verbesserungen der Sicherheit vorgenommen. Es wird empfohlen, die Firmware zu aktualisieren.

