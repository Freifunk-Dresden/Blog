---
layout: post
title: FFDD-Testing Firmware 6.4.5
author: Niklas Merkelt
category:
- News
- Firmware
---

Es steht eine neue TESTING Firmware 6.4.5 bereit. Sie enthält gegenüber 6.4.4 einige Fehlerbehebungen.

[https://download.freifunk-dresden.de/firmware/testing/](https://download.freifunk-dresden.de/firmware/testing/)

Änderungen seit 6.4.4:
* Probleme nach dem ignorieren von Knoten behoben
* Umstellung des Firmware-Download und der Knoten-Registierung auf eine selfsigned CA (Unabhänigkeit von auslaufenden Let's Encrypt Zertifikaten)
* Fehlerhafte Anzeige der WLAN-SSIDs im Webinterface behoben
* Entfernen von Überbleibseln alter fastd Versionen
* Behebung eines Update-Fehlers von 6.0.15 (Fehlerhafter Zustand der Mesh-Wartezeit Konfiguration)
