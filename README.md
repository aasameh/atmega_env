# ATmega Environmental Sensor Breakout PCB

This repository documents a compact environmental measurement breakout PCB built around the ATmega328P.

## Overview

The board combines a low-power 8-bit microcontroller with digital sensors for light, temperature, and humidity monitoring.  
It is intended as a simple platform for logging or transmitting ambient environmental data.

## Main Components

- **Microcontroller:** ATmega328P
- **Ambient Light Sensor:** OPT3004DNPR (digital light sensor)
- **Temperature/Humidity Sensor:** SHT31 (digital sensor)
- **Connectivity:** Header pins for power, programming, and I/O expansion

## Typical Use Cases

- Indoor environment monitoring
- Weather station prototypes
- Sensor breakout integration with larger embedded systems

## Notes

- Sensors communicate digitally, reducing analog noise sensitivity.
- Header-based breakout design simplifies breadboard and prototype integration.

## Repository Structure

```text
atmega_env/
├── ATmega.PDF
├── Design Rule Check - PCB1.drc
├── Design Rule Check - PCB1.html
├── FootprintComparison/
│   └── PCB1.html
├── Gerber/
│   ├── PCB1-macro.APR_LIB
│   ├── PCB1.EXTREP
│   ├── PCB1.GBL
│   ├── PCB1.GBO
│   ├── PCB1.GBP
│   ├── PCB1.GBS
│   ├── PCB1.GM
│   ├── PCB1.GP1
│   ├── PCB1.GP2
│   ├── PCB1.GTL
│   ├── PCB1.GTO
│   ├── PCB1.GTP
│   ├── PCB1.GTS
│   ├── PCB1.REP
│   └── PCB1.apr
├── NC Drill/
│   ├── PCB1-RoundHoles.TX1
│   ├── PCB1-RoundHoles.TX2
│   ├── PCB1-RoundHoles.TXT
│   ├── PCB1-SlotHoles.TXT
│   ├── PCB1.DRR
│   └── PCB1.LDP
├── Status Report.Txt
└── README.md
```

### What each folder/file is for

- **ATmega.PDF**: consolidated design documentation export. It contains the schematic print, 1:1 board print, DRC, and ERC.
- **Design Rule Check - PCB1.drc / .html**: detailed design rule check reports (machine-readable text and browser-readable HTML).
- **FootprintComparison/**: footprint comparison output report.
- **Gerber/**: fabrication Gerber outputs for PCB layers and associated CAM/export report files.
- **NC Drill/**: drill and hole definition outputs for manufacturing.
- **Status Report.Txt**: output generation status summary from the design tool.
