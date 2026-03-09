# Solar Powered Plant Monitoring System

This project presents the design of a solar-powered plant monitoring device with wireless communication capabilities.

The system collects environmental data using sensors and transmits the information via Bluetooth communication.

## Project Overview

The device is designed as a low-power embedded system powered by a solar panel. An energy harvesting circuit manages the power coming from the solar panel and charges a Li-Po battery that powers the system.

The PCB was designed in Altium Designer and integrates power management, sensor connections and wireless communication components.

## System Architecture

The system consists of the following main blocks:

- Solar panel for energy generation
- Energy harvester for power management
- Li-Po battery for energy storage
- Microcontroller for data processing
- Sensors for environmental monitoring
- Bluetooth module for wireless communication
- RF antenna for signal transmission

## System Block Diagram

![System Diagram](images/system_diagram.png)

## PCB Design

The PCB was designed using Altium Designer and includes:

- schematic design
- component placement
- signal routing
- power distribution optimization
- RF antenna integration

Special attention was given to stable power supply routing and proper placement of RF components.

## PCB Layout

![PCB Layout](pcb/pcb_layout.png)

## 3D View

![PCB 3D](pcb/pcb_3d.png)

## Tools Used

- Altium Designer
- Blender 3D creation software
- datasheet analysis

## Documentation

Additional design details, calculations and component selection are available in the project presentation:

[Project Presentation](documentation/project_presentation.pdf)

## Repository Structure

```
plant-monitoring-system
│
README.md
│
schematics
│   schematic.pdf
│
pcb
│   pcb_layout.png
│   pcb_3d.png
│
images
│   system_diagram.png
│
documentation
│   project_presentation.pdf
```
