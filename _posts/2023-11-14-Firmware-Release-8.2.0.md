---
layout: post
title: Firmware Release Firmware 8.2.0
author: Stephan Enderlein
category:
- News
- Firmware
---
Release Router Firmware [8.2.0](https://download.freifunk-dresden.de/firmware/latest/).

**Sicherheits-Update** \
Diese Release Firmware beinhaltet ein Sicherheits-Update, welches die Sicherheit des Routers weiter verbessert und unbedingt aktualisiert werden sollte, sowie weitere Verbesserungen.

Änderungen seit der letzten Release (English):

- LED
  - wifi status LED (GW/Freifunk Status) is not static (instead of blinking)
- WiFi
  - add support for utf8 (emoji) in wifi scan
- Openwrt 22
  - move some routers to openwrt 22 (revert iptables patch)
  - add some new routers
- GUI
  - colorize "Knoten ignorieren"
  - add wetter info
  - add info whether 5GHz meshing is supported or not
  - add configuration switch  to disable 5GHz
- Tethering
  - add configuration switch to enable iOS tethering (default: off, to reduce 50% CPU load on some devices)
- LTE
  - add gl-inet GL-E750 with display support
  - add SIM Pin info
- router
  - add device DLink COVR X1860
- USB
  - add usb serial console login (getty)
- timezone
  - fix storing user input for timezone
- WiFi
  - add 5ghz client mode (WAN: allows using other 5GHz AP as Internet source)
  - WLAN Scan: add infos about encryption
  - remove owl-loader from devices that do not use it
  - fix 5GHz outdoor channel range
- Gateway check
  - reduce check time from 3min -> 1min
- Reboot
  - optimize reboot when configuration was changed (no two reboots anymore)
- bmxd
  - v1.4: fix potential crash and improve code for development
- Splash
  - remove splash competely
- Syslog
  - reduce syslog traces and http error messages
- Sysinfo
  - add wifi infos (htmode, bitrate)
- Others
  - remove old code (nodegroup)
  - add internal config switch to enable/disable STP for WAN/LAN bridge
