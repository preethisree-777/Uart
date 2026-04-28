# UART Communication System

## Project Description

Designed and implemented a UART (Universal Asynchronous Receiver Transmitter) Communication System using Verilog HDL in Xilinx Vivado for reliable serial communication between digital systems.

The project includes Baud Rate Generator, UART Transmitter (TX), and UART Receiver (RX) modules for 8-bit asynchronous serial data transfer using start bit, stop bit, and baud synchronization.

The design was verified through simulation, followed by synthesis, implementation, timing analysis, and power analysis to ensure correct functionality and FPGA efficiency.

---

## Problem Statement

Serial communication is widely used in embedded systems, microcontrollers, and FPGA-based designs. Reliable transmission and reception of data require proper synchronization and protocol handling.

This project solves that by implementing a complete UART communication system with accurate baud rate generation and FSM-based TX/RX control.

---

## Solution Approach

- Designed Baud Rate Generator for clock synchronization
- Developed UART Transmitter for serial data transmission
- Developed UART Receiver for serial data reception
- Used FSM (Finite State Machine) for TX and RX control
- Verified functionality using Verilog Testbench
- Performed synthesis and implementation using Vivado
- Analyzed power consumption and device utilization

---

## Technologies Used

- Verilog HDL
- Xilinx Vivado
- FPGA Design Flow
- RTL Design
- FSM Design
- Timing Analysis
- Power Analysis

---

## Key Features

- 8-bit UART Communication
- Start and Stop Bit Handling
- Baud Rate Synchronization
- FSM-based TX and RX Design
- Low FPGA Resource Utilization
- Successful Timing Closure
- Power Efficient Design

---

## Results

- Successful serial data transmission and reception
- Correct baud tick generation
- Resource Utilization:
  - LUTs: 15
  - Flip-Flops: 14
- Total On-Chip Power: 0.448 W
- Clean implementation with no routing issues

---

## Learning Outcome

This project helped in gaining practical knowledge of:

- UART Protocol Implementation
- Verilog RTL Design
- FSM-based Digital System Design
- Vivado Synthesis and Implementation Flow
- FPGA Optimization and Debugging
