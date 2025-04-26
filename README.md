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
## Details 🗒️:
**FTD Firewall:** The first line of defense between the Internet and your internal network.

**Core Switch:** Main internal switch, connecting to Access Switches and Servers.

**DMZ Switch:** Dedicated to public-facing servers (e.g., Web, Email), separated from the internal LAN.

### VLANs Detail:

User VLAN for employee computers and devices.

Server VLAN for internal application/file servers.

Access Switches: Distribute connections to desks, Wi-Fi APs, printers, etc.

### Optional additions:

VPN configured on the FTD for remote employees.

Redundant links (if budget allows).

Guest Wi-Fi isolated on its own VLAN.
