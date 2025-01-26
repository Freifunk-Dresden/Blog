---
layout: post
title: Release Firmware 8.2.7
author: Stephan Enderlein
category:
- News
- Firmware
---
Release Firmware [8.2.7](http://download.freifunk-dresden.de/firmware/8.2.7/).

Diese Release Firmware beinhaltet folgende Verbesserungen.  

Für einige alte Router, welche auf Openwrt 18 basieren, ist diese Version die letzte.
Openwrt 18 wird schon seit einigen Jahren nicht mehr von openwrt.org unterstützt,
und endet damit auch bei uns. Betroffen sind vorallem Geräte, die nur eine sehr
geringe Leistung und Speicher haben. Openwrt.org ist aktuell bei der Hauptversion 23.

Änderungen seit der letzten Release 8.2.0:

- WiFi: Für Router, wo genügend Speicher verfügbar ist, wurde WPA3 für den Client-Mode hinzugefügt
- Sysinfo: Umbau der Netzwerk-Statistik Sektion
- Firmware Upgrade: Firmware wurde für zukünftige Updates vorbereitet. Einige Router können direkt auf eine zukünftige Version aktualisiert werden. Andere Router müssen zuerst auf diese 8.2.2 wechseln, damit neuere Versionen akzeptiert werden. Grund ist openwrt.org, welche den Upgrade-Prozess nicht optimal eingebaut haben.
- Openvpn: Diese Funktion wurde ausgebaut, da sie nicht verwendet wurde und der Datendurchsatz kaum nutzbar ist.
- Firewall: Es wurden weitere Verbesserungen der Sicherheit vorgenommen. **Es wird empfohlen, die Firmware zu aktualisieren.**
- Backbone Server: Wireguard wird zum Standard
- Backbone Server: Server von Leipzig hinzugefügt
- Passwort: Bugfix beim Setzen von komplizierten Passwörtern
- Community: "Freifunk Geringswalde" hinzugefügt
- Router: GL.inet E750 5Ghz jetzt möglich
- Oberfläche: Fix fehlenden Text auf Backbone/PrivateVPN Seite nach Seiten-neu-laden
- Oberfläche: Fix Fehlerseite auf Kontaktseite
- Oberfläche: Fix Problem, wenn CSS nicht geladen wird
- Oberfläche: Fix kleinere CSS Probleme auf einigen Windows PCs
- Openwrt: Upgrade Openwrt 22 Images (ausgewählte Router) nach 22.03.7
