# System for Automatic Greenhouse

Bachelor thesis project (2024) – Technical University of Cluj-Napoca  
Design and implementation of an **automated greenhouse monitoring and control system**.

## Overview
The system is built around an **ATmega64A microcontroller embedded on a custom 4-layer PCB**, integrating:
- 5 environmental sensors (air temperature and humidity, gas concentrations, soil quality, light, water level)
- Galvanic isolation for external sensor/actuator interfaces
- Wi-Fi module (ESP-12E) communicating via **MQTT** to **ThingsBoard**
- Control of water pump (PWM) and lighting (relay)
- **Takagi-Sugeno fuzzy inference** system regulating water flow based on air temperature and soil humidity

## IoT Integration
- MQTT telemetry to **ThingsBoard** (open-source IoT platform)
- Remote dashboard & data logging
- Accessible from any network (Web UI)

## Main technologies
- ATmega64A, ESP-12E Wi-Fi module
- RS-485 with optocouplers
- Fuzzy logic (Takagi-Sugeno)
- PCB: 4 layers, mixed-signal & isolation

## Repository contents
| File | Description |
|------|-------------|
| `VeliciuVlad_Licenta.pdf` | Complete bachelor thesis and design report |
| `Schematic Prints.PDF` | Electrical schematics |
| `Layers.PDF` | PCB copper layer overview |
| `Assembly Drawings.PDF` | Assembly and placement drawings |
| `PDF3D.PDF` | 3D visualization of the PCB |
| `Bill of Materials.PDF` | Bill of materials |
| `Prezentare.pptx` | Project presentation |
| `Pick Place for PCB1.txt` | Pick-and-place file |
| `Bachelor.pdsprj` | Native PCB design project file |

## Disclaimer
This is my BSc thesis developed in 2024 at UTCN.
Please do not copy or submit this work as your own.
Referencing this repository is allowed.
Native CAD and simulation project files (e.g. Proteus, PSIM) as well as manufacturing files
(Gerbers, pick-and-place) are intentionally not included.

