# Rack Layout

## GEEEKPi DeskPi RackMate T1

- **Rack:** GEEEKPi DeskPi RackMate T1
- **Capacity:** 8U
- **Width:** 10-inch
- **Depth:** 7.87 inches

## Physical U Positions

The rack is documented from **U1 at the top to U8 at the bottom** based on the current physical arrangement provided for the lab.

| U Position | Equipment | Role |
|---|---|---|
| **U1** | GL.iNet GL-BE9300 Flint 3 | Wi-Fi 7 access point |
| **U2** | AC Infinity MULTIFAN S3 | Exhaust fan |
| **U3** | TP-Link TL-SG108E | 8-port managed Gigabit switch |
| **U4** | Raspberry Pi 5 | Pi-hole ad blocker |
| **U5** | Beelink EQ Mini PC / Intel N150 | Jellyfin home media server |
| **U6** | Intel J1900 mini PC | pfSense router/firewall |
| **U7** | ElecVoztile PDU | Rack power distribution |
| **U8** | Noctua NF-F12 5V | Intake fan |

## Airflow

The rack uses a dedicated intake and exhaust fan arrangement:

```text
             Rack top
                |
                v
        +---------------+
 U1    | Flint 3        |
 U2    | EXHAUST FAN    | ---> Exhaust airflow
 U3    | Network switch |
 U4    | Raspberry Pi 5 |
 U5    | Beelink/N150   |
 U6    | pfSense J1900  |
 U7    | PDU            |
 U8    | INTAKE FAN     | <--- Intake airflow
        +---------------+
                ^
                |
             Rack bottom
```

> **Note:** The U positions represent the user's current physical arrangement. Some equipment may not occupy a full rack unit in the conventional rack-mount sense.

## KVM Switch

The lab also uses an **8-port HDMI KVM switch** for centralized local console access.

- **Type:** HDMI KVM switch
- **Ports:** 8 computers / 1 monitor
- **USB:** USB 3.0
- **Video:** Supports up to 4K @ 60 Hz
- **USB peripherals:** Shared keyboard and mouse
- **Switching:** Hotkey switching supported
- **Role:** Centralized keyboard, mouse, and monitor access for multiple computers
- **Exact manufacturer/model:** TBD

The KVM is treated as an **external rack accessory** rather than one of the eight physical rack positions unless its mounting position is documented separately.


