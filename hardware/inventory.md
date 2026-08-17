# Hardware Inventory

## Rack

### GEEEKPi DeskPi RackMate T1 8U 10-inch Mini Server Rack

- **Category:** Rack
- **Model:** DeskPi RackMate T1
- **Height:** 8U
- **Width:** 10-inch
- **Depth:** 7.87 inches
- **Supported equipment:** Network, server, audio, and video equipment
- **Role:** Physical rack for the desk lab

### ElecVoztile PDU

- **Category:** Power distribution unit
- **Voltage:** 125 V
- **Current rating:** 15 A
- **Maximum rated power:** 1,875 W
- **Role:** Rack power distribution

## Cooling

### Noctua NF-F12 5V

- **Category:** Rack cooling fan
- **Size:** 120 mm × 25 mm
- **Voltage:** 5 V
- **Speed:** Up to 1,500 RPM
- **Connector:** 3-pin
- **Power:** USB-A power adapter
- **Role:** Intake fan
- **Airflow direction:** Intake into the rack

### AC Infinity MULTIFAN S3

- **Category:** Rack cooling fan
- **Size:** 120 mm
- **Power:** USB
- **Certification:** UL-certified
- **Role:** Exhaust fan
- **Airflow direction:** Exhaust out of the rack

## Networking

### GL.iNet GL-BE9300 Flint 3

- **Category:** Wireless access point
- **Wireless:** Wi-Fi 7
- **Role:** Access point
- **Upstream:** Connected to the pfSense router
- **Routing role:** Not the primary router
- **Firmware version:** TBD
- **Management address:** TBD

### TP-Link TL-SG108E 8-Port Gigabit Easy Smart Managed Switch

- **Category:** Network switch
- **Model:** TL-SG108E
- **Ports:** 8 × Gigabit Ethernet
- **Management:** Easy Smart Managed
- **Form factor:** Desktop / wall-mount
- **Construction:** Metal chassis with shielded ports
- **Features:** QoS, VLAN, IGMP, LAG
- **Role:** Network switching
- **Management address:** TBD
- **Firmware version:** TBD

### Intel J1900 Mini PC / pfSense Firewall

- **Category:** Firewall/router appliance
- **CPU:** Intel J1900
- **Ethernet:** 4 × Intel i210
- **RAM:** 4 GB
- **Storage:** 64 GB SSD
- **Operating system:** pfSense
- **pfSense version:** TBD
- **Role:** Primary router and firewall
- **Management address:** TBD

## Computer

### Beelink EQ Mini PC / Alder Lake-N150

- **Category:** Mini PC / home media server
- **Model:** Beelink EQ Mini PC
- **CPU:** Intel N150, up to 3.6 GHz, 4 cores / 4 threads
- **RAM:** 12 GB LPDDR5
- **Internal storage:** 500 GB SSD
- **Additional storage:** 2 TB Seagate SSD
- **Video:** 4K 60 Hz, dual HDMI
- **Wireless:** Wi-Fi 6 / Bluetooth 5.2
- **Networking:** Dual 2.5 GbE
- **Operating system:** Linux Mint
- **Primary role:** Home media server
- **Media software:** Jellyfin
- **Media storage:** Movies and TV shows stored on the 2 TB Seagate SSD
- **Management address:** TBD

### Raspberry Pi 5

- **Category:** Single-board computer
- **Model:** Raspberry Pi 5
- **RAM:** 8 GB
- **Storage:** 128 GB SSD
- **Operating system:** TBD
- **Primary role:** Pi-hole ad blocker
- **Services:** Pi-hole ad blocker
- **Management address:** TBD
- **Cooling:** TBD

## Console / Peripheral Management

### KCEVE 8-Port HDMI KVM Switch

- **Category:** KVM switch
- **Manufacturer:** KCEVE
- **Computer inputs:** 8
- **Monitor outputs:** 1
- **Video:** HDMI, up to 4K @ 60 Hz
- **USB:** USB 3.0
- **Shared peripherals:** Keyboard and mouse
- **Switching:** Hotkey switching supported
- **Role:** Centralized keyboard, mouse, and monitor access for multiple computers
- **Rack position:** External rack accessory / position TBD

#### KVM Port Assignments

| KVM Port | Connected Computer | Role |
|---|---|---|
| **Port 1** | Intel J1900 mini PC | pfSense router/firewall |
| **Port 2** | Beelink EQ Mini PC / N150 | Home media server / Jellyfin |
| **Port 3** | Raspberry Pi 5 | Pi-hole ad blocker |
| **Port 4** | Unassigned | Available |
| **Port 5** | Unassigned | Available |
| **Port 6** | Unassigned | Available |
| **Port 7** | Unassigned | Available |
| **Port 8** | Unassigned | Available |

## Missing Details to Fill In

- GL.iNet Flint 3 firmware version and management address
- pfSense version and management address
- TP-Link switch management address and firmware version
- Beelink management address
- Raspberry Pi 5 operating system, management address, and cooling
- Hostnames
- IP addresses / VLANs
- Power connections and PDU outlet assignments
- Network cabling
- Remaining KVM port assignments
