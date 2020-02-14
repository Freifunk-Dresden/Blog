---
layout: post
title: FFDD-Server Update v1.1.0
author: Sven Kinne
category: firmware
---

Wir haben soeben die neue FFDD-Server Version 1.1.0 freigegeben.
Dieses ist kein automatisches Update und muss manuell ausgeführt werden.

Alle Änderungen im Überblick findet ihr im CHANGELOG:
https://github.com/Freifunk-Dresden/ffdd-server/blob/master/CHANGELOG.md

Um das Update nun durchzuführen brauchst du nur folgendes tun:

```bash
sh -c "$(curl -fsSL http://2ffd.de/ffdd-server_manuell_update)"
```

danach noch ein `reboot`.

Das war es schon. :)
