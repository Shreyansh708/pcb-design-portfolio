# PCB Design Portfolio

Electronics PCB design projects developed using KiCad, covering schematic capture, PCB layout, routing, design verification, and manufacturing outputs.

---

## 01 — Single LED PCB

**Status:** Completed  
**EDA Tool:** KiCad 10.0.5  
**Board Type:** 2-layer PCB  
**Board Dimensions:** 25.05 mm × 44.05 mm  
**Board Thickness:** 1.6 mm
### PCB Layout

![Single LED PCB Layout](single-led-pcb-layout.png)

### Schematic

![Single LED PCB Schematic](single-led-pcb-schematic.png)

### Overview

A compact single-LED PCB designed through the complete PCB development workflow, from schematic capture to PCB layout and manufacturing-output generation.

### Design Workflow

- Schematic capture
- Component placement
- PCB layout and routing
- Board outline definition
- Design-rule verification
- Gerber generation
- PTH and NPTH drill-file generation

### Project Files

The repository contains:

- KiCad project file (`.kicad_pro`)
- KiCad schematic (`.kicad_sch`)
- KiCad PCB layout (`.kicad_pcb`)
- Gerber manufacturing files
- PTH and NPTH drill files
- Gerber job file

### Tools

**KiCad 10.0.5**

---


## 02 — AstraDrive BLDC/PMSM Controller

**Status:** Work in Progress  
**EDA Tool:** KiCad  
**Controller:** STM32G474RE  
**System:** 48 V 3-phase BLDC/PMSM motor controller

### Overview

A hardware development project for a 48 V 3-phase BLDC/PMSM motor controller, designed around an STM32G4 microcontroller and intended for applications such as robotics, AGVs, drones, and electric mobility.

The project is being developed as a hierarchical KiCad design with dedicated functional subsystems.

### Current Architecture

The design currently includes:

- STM32G474RE control subsystem
- 3-phase MOSFET bridge
- Gate-driver subsystem
- Current sensing
- Hall-sensor feedback
- Encoder interface
- DC-bus voltage sensing
- Temperature monitoring
- CAN-FD interface
- Display/UI interface
- Programming/debug interface

### Development Status

The system architecture and hierarchical schematic are currently under development. PCB component placement and routing are the next stages of development.

![AstraDrive System Architecture](astradrive-system-architecture.png)

## About

Electrical & Electronics Engineering undergraduate interested in:

- Embedded Systems
- ARM Microcontrollers
- PCB Design
- IoT
- Motor Control
- Digital Electronics
- Hardware Development
- Low-level Firmware
