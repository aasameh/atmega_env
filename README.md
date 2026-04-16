# ATmega Environmental Sensor Breakout PCB

This repository documents a compact environmental measurement breakout PCB built around the **ATmega328P**.

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
