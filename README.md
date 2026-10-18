# LunarGateway

> Open-source platform for sleep-onset research: hardware, firmware, signal processing, and software.

LunarGateway combines custom hardware, physiological sensing, signal processing, and software into an experimental platform for studying the sleeping mind.

The name is a working codename. Scope and architecture are still open.

---

## Status

Work in progress.

## Objectives

- **Document** hardware, firmware, software, protocols, and design decisions.
- **Reproduce** builds and development environments.
- **Evaluate** the architecture and replace obsolete or fragile components.
- **Experiment** with alternative implementations.

The immediate goal is a working, documented baseline. A full rewrite or new features are not assumed.

## Hardware

### Components

The bill of materials is a reference until the hardware is verified. Component availability and electrical compatibility are not yet confirmed.

### PCB

Schematics, layouts, and manufacturing files are unverified. Boards can be reproduced via PCB fabrication or milling. Document any modifications separately from the base design.

Areas to cover:

- Bill of materials and component availability
- Schematics and PCB layouts
- Sensor interfaces and signal acquisition
- Microcontroller and firmware
- Substitutes for unavailable components

## Software

### Architecture

Each component's responsibilities and interfaces are identified first; then it is decided what to keep, repair, replace, or remove.

Areas to cover:

- Web application and UI
- Mobile application and device communication
- Firmware and hardware integration
- Physiological signal acquisition and processing
- Sleep-stage classification
- Data formats, persistence, and inter-process communication
- Build instructions, dependencies, and runtime requirements

### Web Application

Launch:

```sh
...
```
