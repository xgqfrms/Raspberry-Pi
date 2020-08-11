# wireless


https://www.raspberrypi.org/documentation/configuration/wireless/access-point-routed.md

https://www.raspberrypi.org/documentation/configuration/wireless/access-point-bridged.md



## WLAN AP

```md
                                         +- RPi -------+
                                     +---+ 10.10.0.2   |          +- Laptop ----+
                                     |   |     WLAN AP +-)))  (((-+ WLAN Client |
                                     |   | 192.168.4.1 |          | 192.168.4.2 |
                                     |   +-------------+          +-------------+
                 +- Router ----+     |
                 | Firewall    |     |   +- PC#2 ------+
(Internet)---WAN-+ DHCP server +-LAN-+---+ 10.10.0.3   |
                 |   10.10.0.1 |     |   +-------------+
                 +-------------+     |
                                     |   +- PC#1 ------+
                                     +---+ 10.10.0.4   |
                                         +-------------+
```
