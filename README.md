# ESP32-S3 IoT Development Board (KiCad PCB Design)

A custom **4-layer ESP32-S3 IoT development board** designed in **KiCad** for embedded and IoT applications.

> **Project Status:** PCB Design Completed (Not Fabricated)

---

# Project Overview

This project focuses on the complete schematic capture and PCB layout of an ESP32-S3 based development board intended for IoT and embedded system applications.

The board was designed following good PCB design practices, including component placement, routing, power distribution, USB differential pair routing, and design rule verification.

This repository contains the complete KiCad design files for learning, portfolio, and reference purposes.

---

# Features

- ESP32-S3-WROOM module
- 4-Layer PCB Design
- USB Type-C Interface
- USB ESD Protection
- 3.3V Power Regulation
- BOOT and RESET Buttons
- UART Programming Header
- QWIIC (I²C) Connector
- GPIO Expansion Header
- Power Status LED
- Design Rule Check (DRC) Verified
- Electrical Rule Check (ERC) Verified

---

# Tools Used

- KiCad 9
- PCB Editor
- Schematic Editor
- Interactive Router
- 3D Viewer

---

# Design Highlights

- Designed complete schematic from scratch
- Created 4-layer PCB layout
- Routed USB differential pair
- Implemented proper power distribution
- Added decoupling capacitors following ESP32 recommendations
- Implemented USB ESD protection
- Added programming and debugging interfaces
- Planned antenna keep-out region
- Performed ERC and DRC verification

---

# Hardware Specifications

| Feature | Details |
|----------|---------|
| MCU | ESP32-S3-WROOM |
| PCB Layers | 4 |
| USB | USB Type-C |
| Power | 3.3V |
| Programming | UART |
| Communication | UART, SPI, I²C |
| Expansion | QWIIC Connector |
| Design Software | KiCad 9 |

---

# Repository Structure

```
ESP32_S3_TESTBOARD
│
├── Hardware
│   ├── ESP32_S3_TESTBOARD.kicad_pro
│   ├── ESP32_S3_TESTBOARD.kicad_sch
│   └── ESP32_S3_TESTBOARD.kicad_pcb
│
├── Images
│   ├── PCB_Top.png
│   ├── PCB_Bottom.png
│   ├── 3D_Top.png
│   ├── 3D_Bottom.png
│   └── Schematic.png
│
├── Documents
│
├── README.md
├── LICENSE
└── .gitignore
```

---

# Images

## Schematic 
<img width="1063" height="751" alt="Schematic" src="https://github.com/user-attachments/assets/c19ac4d0-3758-4143-b158-5836db20087b" />


---

## PCB Top

<img width="1287" height="818" alt="pcb_top" src="https://github.com/user-attachments/assets/0b9a4e1d-1963-423f-9676-1cb700308431" />


## 3D Top View

<img width="1485" height="967" alt="3D Top" src="https://github.com/user-attachments/assets/61393fbb-40db-4919-9d76-6c71da8642ef" />


---

## 3D Bottom View

<img width="1125" height="811" alt="3D BOTTOM" src="https://github.com/user-attachments/assets/6030091d-8f30-4d60-96e0-d18db2339375" />

---

# PCB Design Workflow

1. Component Selection
2. Schematic Capture
3. Footprint Assignment
4. PCB Floor Planning
5. Component Placement
6. Interactive Routing
7. USB Differential Pair Routing
8. Power Plane Design
9. ERC Verification
10. DRC Verification
11. 3D Inspection

---

# Learning Outcomes

Through this project I gained practical experience in:

- Multi-layer PCB Design
- Schematic Capture
- ESP32 Hardware Design
- USB Interface Design
- PCB Component Placement
- Differential Pair Routing
- Power Distribution
- PCB Design Rules
- ERC and DRC Validation
- KiCad PCB Design Workflow

---

# Future Improvements

- PCB Fabrication
- Board Assembly
- Hardware Bring-up
- Firmware Development
- Functional Testing
- Power Consumption Analysis
- Sensor Expansion

---

# Note

This repository contains the **PCB design only**.

The hardware has **not been fabricated or tested**, and this project is intended to demonstrate PCB design skills using KiCad.

---

# Author

**Himanshu Pawar**

Electronics & Telecommunication Engineer

- LinkedIn: https://www.linkedin.com/in/himanshu-pawar-a74b732a9
- GitHub: https://github.com/himanshu17890

---

If you found this project useful, consider giving it a ⭐.
