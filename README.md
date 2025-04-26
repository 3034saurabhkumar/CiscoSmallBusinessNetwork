# CiscoSmallBusinessNetwork 🛜
Designed and implemented a secure network infrastructure for a small business using Cisco routers, switches and Firewalls (FTD).

## Topology Diagram 🕸️

```
                     Internet
                        |
                     [ ISP Modem ]
                        |
                     [ FTD Firewall ]
                        |
                +----------------+
                |                |
         [ Core Switch ]    [ DMZ Switch ]
                |                |
        +-------+-------+    +---+---------+
        |       |       |    |             |
   [User VLAN] [Server VLAN] [Web Server] [Email Server]
        |
    [Access Switches]
        |
   [User Devices (PCs, Printers, Phones)]
```
