# Desk Pi Rack

Documentation and inventory for the desk-mounted home lab / mini server rack.

## Rack

- **Rack:** GEEEKPi 8U, 10-inch Mini Server Rack
- **Rack size:** 8U
- **Rack width:** 10-inch
- **PDU:** ElecVoztile 125 V / 15 A / 1,875 W

## Current Inventory

| Category | Device | Specifications | Role |
|---|---|---|---|
| Rack | GEEEKPi 8U 10-inch Mini Server Rack | 8U, 10-inch | Physical rack |
| Power | ElecVoztile PDU | 125 V, 15 A, 1,875 W | Power distribution |
| Network | GL.iNet GL-BE9300 Flint 3 | Wi-Fi 7 | Access point |
| Firewall | Intel J1900 mini PC | 4 × Intel i210 Ethernet, 4 GB RAM, 64 GB SSD | pfSense router/firewall |
| Switch | TP-Link TL-SG108E | 8 × Gigabit Ethernet, managed | Network switching |
| Compute | Beelink EQ Mini PC / N150 | 12 GB LPDDR5, 500 GB SSD + 2 TB Seagate SSD, Linux Mint | Home media server / Jellyfin |
| Compute | Raspberry Pi 5 | 8 GB RAM, 128 GB SSD | Pi-hole ad blocker |

## Documentation Status

This inventory is a work in progress. Specifications that have not yet been provided are intentionally marked **TBD** rather than guessed.

## Planned Documentation

- Rack layout and U positions
- Network topology
- Router/access-point configuration
- pfSense firewall details
- Switch model and configuration
- Beelink operating system and configuration
- Raspberry Pi OS and configuration
- Hostnames and IP addressing
- Power supplies and power distribution
- PDU outlet assignments
- Cooling and cable management
- Backup and maintenance notes

## Security Note

Do not commit passwords, API keys, private keys, Wi-Fi passwords, VPN secrets, or other credentials to this repository. Avoid publishing public IP addresses or other sensitive network information unless intentionally documented.
