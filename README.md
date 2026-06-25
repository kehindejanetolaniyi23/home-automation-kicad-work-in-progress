# Home Automation Relay and Power Monitoring PCB — Work in Progress

This repository contains my ongoing KiCad PCB design for a home automation relay and power monitoring board.

The project is designed as a multi-channel control and monitoring board for home automation applications. It combines relay switching, power monitoring, sensing interfaces, optocoupler isolation, and onboard power regulation into one PCB design.

This project is still in progress, and I am continuing to improve the routing, board outline, component spacing, and design rule compliance.

## Project Overview

The goal of this project is to design a PCB that can support home automation control and electrical monitoring functions. The board includes relay outputs for switching external loads, sensing sections for voltage/current monitoring, and interface connections for a controller module.

The design is being developed in KiCad and currently includes both schematic and PCB layout files.

## Main Features

* Multi-channel relay switching section
* Optocoupler isolation stage
* Voltage sensing section
* Current sensing transformer section
* Onboard power regulation section
* Screw terminal input/output connectors
* Status indicator LEDs
* Controller/header interface
* Two-layer PCB layout
* KiCad schematic and PCB layout files

## Tools Used

* KiCad
* KiCad Schematic Editor
* KiCad PCB Editor
* KiCad Design Rules Checker

## Repository Files

This repository includes:

* `homeautomation2.kicad_pro` — KiCad project file
* `homeautomation2.kicad_sch` — schematic design file
* `homeautomation2.kicad_pcb` — PCB layout file
* Screenshot images showing the schematic, PCB layout, and current DRC result

## Current Status

Status: **Work in Progress**

The schematic and PCB layout have been created and opened successfully in KiCad. The design already contains the major functional blocks for relay control, sensing, power regulation, and external wiring connections.

The PCB layout is still being improved. Current work includes:

* Completing remaining unrouted connections
* Fixing board outline issues
* Improving component spacing
* Cleaning up silkscreen placement
* Resolving DRC errors and warnings
* Preparing the board for a cleaner final layout
* Generating Gerber files only after the design passes final checks


## Design Notes

The board is intended to combine control and monitoring functions in a compact home automation PCB. The relay section is used for switching loads, while the sensing section supports electrical monitoring. Optocouplers are included to improve isolation between the control and switching sections.

The current PCB layout is functional as a design draft, but it is not yet marked as manufacturing-ready. I am still refining the routing and resolving design rule issues before producing final Gerber fabrication files.

## Next Improvements

The next development steps are:

1. Complete all remaining PCB routing.
2. Fix the Edge.Cuts board outline.
3. Resolve all Design Rule Check errors.
4. Improve relay, terminal block, and sensing section spacing.
5. Clean up text labels and silkscreen placement.
6. Re-run schematic-to-PCB checks.
7. Re-run DRC until the project has zero errors.
8. Export Gerber and drill files after the design is fully cleaned.

## Project Purpose

This project demonstrates my ongoing KiCad PCB design workflow, including schematic capture, PCB layout development, routing, DRC checking, and iterative board improvement.

The design is still under development and will be updated as improvements are made.
