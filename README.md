# Radio-Controlled Multi-Functional Clock Synthesis on Xilinx Zynq-7000 FPGA Board

## Overview
This project demonstrates the development of a multi-functional clock system using VHDL on the Xilinx Zynq-7000 FPGA board. The clock features time & date display, alarm functionalities, and is controlled by a finite state machine (FSM) to coordinate various operations. The design flow was executed using Xilinx Vivado, covering simulation, synthesis, and post-implementation verification for precise clock performance.

## Features
- **Time & Date Display**: A fully functional clock capable of displaying time and date on an external display.
- **Alarm System**: Set and trigger alarms at predefined times.
- **Display Control**: Optimized VHDL code for controlling the display, ensuring real-time updates.
- **Finite State Machine (FSM)**: Used to manage the coordination between different clock modes (e.g., time, alarm).
- **Vivado Design Flow**: Complete design and implementation workflow including simulation, synthesis, place & route, and post-implementation verification.

## Design Flow
1. **Simulation**: VHDL modules were simulated to verify functionality.
2. **Synthesis**: The design was synthesized into a netlist for FPGA implementation.
3. **Place & Route**: The synthesized design was placed and routed onto the Zynq-7000 FPGA.
4. **Post-Implementation Verification**: Ensured accurate performance through timing analysis and clock cycle verification.

## Technologies Used
- **VHDL**: Hardware description language used to code the clock’s functionality.
- **Xilinx Zynq-7000 FPGA**: The hardware platform on which the clock was implemented.
- **Xilinx Vivado**: The toolchain used for simulation, synthesis, place & route, and verification.

## How to Run the Project
1. **Install Xilinx Vivado**: Download and install Vivado on your system.
2. **Clone the Repository**: 
    ```bash
    git clone https://github.com/TheMechanicHulk/Multi-Functional-Clock-FPGA.git
    ```
3. **Open Project in Vivado**: Load the VHDL files into a new project in Vivado.
4. **Simulate & Synthesize**: Use Vivado’s simulation tools to verify functionality, then synthesize the project.
5. **Program FPGA**: Upload the synthesized design onto a Xilinx Zynq-7000 FPGA board and observe the clock’s operation.

## File Structure
- `src/`: Contains VHDL source code.
- `constraints/`: Contains FPGA pin configuration files.
- `simulation/`: Contains testbench files for simulating the clock.
- `docs/`: Contains documentation and design details.

## Future Work
- Add support for daylight saving time.
- Implement power-saving modes for alarm operations.

## Acknowledgements
Special thanks to the Xilinx Vivado community for the extensive support and resources provided for FPGA development.
