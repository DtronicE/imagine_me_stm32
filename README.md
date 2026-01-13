My First STM32 Hardware Design: Custom Development Board
🚀 Overview
This repository contains the design files for my first custom-built STM32 development board. Moving beyond hobbyist modules, this project represents a deep dive into professional-grade ARM Cortex-M architecture and custom PCB engineering.

🛠 Technical Highlights
Core Microcontroller: Designed around the STM32 architecture for high-performance processing and flexible I/O control.

Power System: On-board LDO regulation to manage the 3.3V power requirements of the STM32 chip.

Debugging Interface: Integrated SWD (Serial Wire Debug) port for flashing firmware and real-time hardware debugging.

Custom Footprints: All component footprints, including the main MCU and peripheral connectors, were manually verified against official datasheets.

📐 Design Specifications
Layer Count: 2-Layer high-quality FR4.

Grounding Strategy: Implemented a solid Ground Plane (GND) on both layers to ensure signal integrity and reduce electromagnetic noise.

Routing: Optimized signal paths with trace widths calculated for power and speed requirements.

DRC Status: 100% Passed (Zero electrical errors).
