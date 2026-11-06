# My First STM32 Custom Development Board

## Overview
This repository contains the design files for my first custom-built STM32 development board. The project was created as a hands-on way to move beyond off-the-shelf modules and design a small, self-contained board around an STM32 microcontroller.

The board is centered around the STM32F103C8T6 (Blue Pill class MCU), with USB, UART, I2C, and SWD support included in the design. The files are prepared for editing and refinement in KiCad.

## Hardware Features
- STM32F103C8T6 microcontroller
- 3.3V regulated power supply for the MCU and peripherals
- SWD programming and debugging header
- USB device interface for serial communication and debugging
- USART1 support for UART communication
- I2C2 support for peripheral connectivity
- Solid ground plane for improved signal integrity
- 2-layer FR4 PCB implementation
- Custom symbol and footprint work in the KiCad project

## Technical Highlights
- Core microcontroller: STM32F103C8T6-based design
- Power system: 3.3V regulation for the MCU and supporting circuitry
- Debugging interface: SWD port for flashing and debugging
- Communication interfaces: USB device support, I2C2, and USART1
- PCB implementation: 2-layer FR4 layout with a solid ground plane
- Library work: manually verified footprint and symbol data against datasheet references when applicable

## Design Specifications
- Layer count: 2-layer FR4 board
- Grounding strategy: continuous ground plane used on both layers to improve signal integrity and reduce noise
- Routing: signal paths kept short and organized for a clean, manageable first-pass PCB layout
- DRC status: design checks completed successfully with no electrical errors reported in the project workflow

## Project Contents
- `stm32.kicad_sch` — schematic
- `stm32.kicad_pcb` — PCB layout
- `design1.ioc` — STM32CubeMX project configuration
- `New_Library_0.kicad_sym` — custom symbol library
- `README.md` — project overview and notes

## Notes
This project represents a learning-focused board design and is intended as a practical embedded hardware exercise. Improvements and revisions can be made as the design evolves.

## Status
The repository currently contains the KiCad source files and the associated project configuration needed to continue refining the board design.
