---
layout: post
title: FFDD-Release Firmware 7.0.1
author: Stephan Enderlein
category:
- News
- Firmware
---

Eine neue offizielle Release steht nun wieder zur Verfügung.

http://download.freifunk-dresden.de/firmware/7.0.1/

Es wurden verschiedene Anpassungen und neue Funktionen
hinzugefügt, um die optimale Netzfunktionalität zu gewährleisten.
Bitte führt eine Aktualisierung der Router durch. Bei Firmware Versionen älter als 6.4.4 muss leider die Firmware
manuell über die Oberfläche eingespielt werden, da Let's Encrypt (externer Zertifikatsanbieter) Änderungen
vorgenommen hat, auf die wir leider keinen Einfluss haben.
Mit der neuen Version haben wir daher Änderungen diesbezüglich vorgenommen, um dieses Problem in Zukunft
auszuschliessen.

Viele Router nutzen noch eine sehr alte Firmware und werden nicht aktiv betreut. 
Wir bitten *DRINGEND* darum, diese Router zu aktualisieren, da diese durch die Weiterentwicklung des Netzes
nicht mehr funktionieren könnten. Wir müssen regelmässig Anpassungen am Netz vornehmen, und die Funktionalität
aufrecht zu erhalten. Router mit alter Firwmare würden diese Entwicklung blockieren. Daher können wir
auf diese keine Rücksicht mehr nehmen.

Neuerungen/Änderungen:
* Probleme nach dem ignorieren von Knoten behoben
* Umstellung des Firmware-Download und der Knoten-Registierung auf eine selfsigned CA (Unabhänigkeit von auslaufenden Let's Encrypt Zertifikaten)
* Fehlerhafte Anzeige der WLAN-SSIDs im Webinterface behoben
* Entfernen von Überbleibseln alter fastd Versionen
* Behebung eines Update-Fehlers von 6.0.15 (Fehlerhafter Zustand der Mesh-Wartezeit Konfiguration)
* Anpassungen in Statistik, Firewall

Neuerungen seit letzter Offizieller Version:
* 802.11s meshing
* 5GHz Access Point hinzugefügt
* 5GHz indoor meshing
* Wireguard backbone
* Verbesserung der Oberfläche (wlan scan, syslog, nodes)
* Überarbeitung der Netzwerk-Interfaces
* Neue Router hinzugefügt
* Sprung auf neue Openwrt Version (Freifunk basiert auf Openwrt)
