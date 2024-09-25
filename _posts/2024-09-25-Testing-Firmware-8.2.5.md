---
layout: post
title: Testing Firmware 8.2.5
author: Stephan Enderlein
category:
- News
- Firmware
---
Testing Firmware [8.2.5](http://download.freifunk-dresden.de/firmware/testing-8.2.5/).

Diese Testing Firmware beinhaltet weitere Verbesserungen. Sie soll in Kürze in
eine neue Release führen.

Änderungen seit der letzten Release 8.2.0:
- WiFi: Für Router, wo genügend Speicher verfügbar ist, wurde WPA3 für den Client-Mode hinzugefügt
- Sysinfo: Umbau der Netzwerk-Statistik Sektion
- Firmware Upgrade: Firmware wurde für zukünftige Updates vorbereitet. Einige Router können direkt auf eine zukünftige Version aktualisiert werden. Andere Router müssen zuerst auf diese 8.2.2 wechseln, damit neuere Versionen akzeptiert werden. Grund ist openwrt.org, welche den Upgrade-Prozess nicht optimal eingebaut haben.
- Openvpn: Diese Funktion wurde ausgebaut, da sie nicht verwendet wurde und der Datendurchsatz kaum nutzbar ist.
- Firewall: Es wurden weitere Verbesserungen der Sicherheit vorgenommen. Es wird empfohlen, die Firmware zu aktualisieren.
- Backbone Server: Wireguard wird zum Standard
- Backbone Server: Server von Leipzig hinzugefügt
- Passwort: Bugfix beim Setzen von komplizierten Passwörtern
- Community: "Freifunk Geringswalde" hinzugefügt
- Router: GL.inet E750 5Ghz jetzt möglich
- Oberfläche: Fix fehlenden Text auf Backbone/PrivateVPN Seite nach Seiten-neu-laden
- Oberfläche: Fix Fehlerseite auf Kontaktseite
- Oberfläche: Fix Problem, wenn CSS nicht geladen wird
- Openwrt: Upgrade Openwrt 22 Images nach 22.03.7
