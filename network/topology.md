# Network Topology

## Current Architecture

The desk lab uses the Intel J1900 mini PC running pfSense as the primary router and firewall. The GL.iNet Flint 3 is configured as a wireless access point rather than the primary router.

```text
                    Internet
                       |
                       v
              +------------------+
              | Intel J1900 PC   |
              |     pfSense      |
              |  4 × Intel i210  |
              +------------------+
                       |
                       v
              +------------------+
              | TP-Link TL-SG108E|
              | 8-Port Gigabit   |
              | Easy Smart Switch |
              +------------------+
                  |           |
                  |           +--------------------+
                  |                                |
                  v                                v
          +---------------+                +----------------+
          | Beelink N150  |                | Raspberry Pi 5 |
          | Jellyfin      |                | Pi-hole        |
          | Media Server  |                |                |
          +---------------+                +----------------+

                       |
                       v
              +------------------+
              | GL.iNet Flint 3  |
              | Wi-Fi 7          |
              | Access Point     |
              +------------------+
```

## Network Roles

### pfSense Mini PC

- **Hardware:** Intel J1900 mini PC
- **Ethernet:** 4 × Intel i210
- **RAM:** 4 GB
- **Storage:** 64 GB SSD
- **Role:** Primary router and firewall
- **Operating system:** pfSense

### GL.iNet GL-BE9300 Flint 3

- **Role:** Wireless access point
- **Wireless:** Wi-Fi 7
- **Upstream:** Connected to the pfSense network
- **Routing role:** Not the primary router

### TP-Link TL-SG108E

- **Role:** Managed Ethernet switch
- **Ports:** 8 × Gigabit Ethernet
- **Features:** QoS, VLAN, IGMP, LAG

### Beelink N150

- **Role:** Home media server
- **Service:** Jellyfin
- **Primary storage:** 500 GB SSD
- **Media storage:** 2 TB Seagate SSD

### Raspberry Pi 5

- **RAM:** 8 GB
- **Storage:** 128 GB SSD
- **Role:** Network services
- **Service:** Pi-hole ad blocker


