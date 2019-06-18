---
layout: post
title: FFDD-Server Update v1.0.6_fix5
author: Sven Kinne
category: Firmware
---

Ein neues Update für die Gateway Server ist erschienen.

#### Neuerungen:
- **fastd:** add support to restrict any new connection to a server. should be used when server has too much connections and is overloaded. in this case we must change backbones in clients

##### New *`/etc/nvram.conf`* Option:

```
# to accept all in comming connection, set this to 0 or remove this line.
# When set to 1, only already known connections are accepted. this may be used
# to prevent overloading a server.
fastd_restrict=0
```

Alle Update-News auf [Github](https://github.com/Freifunk-Dresden/ffdd-server/blob/master/UPDATES.md).
