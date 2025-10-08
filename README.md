# Open CNC - Large Format CNC Machine

An open-source CNC machine designed to handle full sheets of plywood (4x8 feet) using easily sourced parts and open-source software.

## Project Overview

This project aims to create a fully functional, large-format CNC machine that can be built with readily available components and open-source tools. The target build area is 4x8 feet to accommodate standard plywood sheets.

### Key Design Goals

- **Large Format**: 4x8 foot build area
- **Easy to Source Parts**: Use common, affordable components
- **Open Source**: All designs, software, and documentation freely available
- **Safety First**: Include comprehensive safety features and documentation
- **Maintainable**: Simple design for easy maintenance and upgrades

## Project Structure

### `/docs/`

Documentation for building, operating, and maintaining the CNC

- `assembly/` - Step-by-step assembly instructions
- `bom/` - Bill of Materials with part numbers and suppliers
- `guides/` - User guides, tutorials, and how-tos
- `maintenance/` - Maintenance schedules and procedures
- `safety/` - Safety guidelines and emergency procedures

### `/hardware/`

Physical hardware designs and models

- `cad/` - CAD files for frame and components (Fusion 360, FreeCAD, etc.)
- `stl/` - 3D printable parts
- `drawings/` - Technical drawings and schematics

### `/software/`

Software components for controlling the CNC

- `firmware/` - Controller firmware (GRBL, Marlin, etc.)
- `control/` - Computer control software and interfaces
- `utilities/` - Helper scripts and utilities

### `/electronics/`

Electronic designs and documentation

- `schematics/` - Circuit diagrams and wiring diagrams
- `pcb/` - PCB design files
- `gerber/` - Manufacturing files for PCBs

### `/mechanical/`

Mechanical design documentation

- `frame/` - Main frame and structural components
- `gantry/` - Gantry and X/Y axis designs
- `z-axis/` - Z-axis and spindle mount designs
- `components/` - Individual component specifications

### `/testing/`

Testing and calibration procedures

- `calibration/` - Axis calibration and tuning guides
- `procedures/` - Testing procedures and checklists

### `/contributing/`

Guidelines for contributors

- Contribution guidelines
- Coding standards
- Design standards

### `/media/`

Visual content

- `photos/` - Build photos and progress updates
- `videos/` - Assembly videos and demonstrations
- `renderings/` - 3D renderings and animations

### `/prototypes/`

Prototype designs and testing results

### `/research/`

Research notes, component evaluations, and design decisions

## Getting Started

1. Review the Bill of Materials in `docs/bom/`
2. Follow the assembly guide in `docs/assembly/`
3. Install firmware from `software/firmware/`
4. Set up control software from `software/control/`
5. Calibrate using guides in `testing/calibration/`

## Contributing

See `contributing/` for guidelines on how to contribute to this project.

## License

This project is licensed under the [MIT License](LICENSE) - see the LICENSE file for details.

## Safety Notice

Building and operating CNC machines involves significant safety risks. Always follow safety guidelines in `docs/safety/` and use appropriate personal protective equipment.
