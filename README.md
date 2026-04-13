# Frequency-Divider-Verilog-
Developed and validated a parameterized frequency divider in Verilog using sequential logic and counters. Functionality was verified through testbench simulation and waveform analysis.
Overview
This project implements a parameterized frequency divider using Verilog HDL. It generates a lower-frequency output clock from a high-frequency input clock using a counter-based approach.

Features
Configurable division factor using a parameter (DIVISOR)
Synthesizable RTL design
Simple and efficient counter-based implementation
Verified using simulation and waveform analysis
Working Principle
A counter increments on every clock cycle. When the counter reaches the specified divisor value, the output clock toggles and the counter resets.

Output frequency is given by:

f_out = f_in / (2 × DIVISOR)

Simulation
Simulator: Icarus Verilog (via EDA Playground)
Waveform Viewer: EPWave
The design was tested using a Verilog testbench and verified through waveform observation.

Results
Input clock: High-frequency signal
Output clock: Reduced frequency based on the divisor
Correct division behavior confirmed via waveform
Concepts Used
Sequential Logic
Counters
Clock Division
Flip-Flops
Timing Analysis
Future Improvements
Programmable divider with runtime control
Duty cycle correction
FPGA implementation (Quartus)
Multi-frequency output generation
How to use : -Open Intel Quartus Prime lite -New project -Synthesize for Netlist and Run RTL simulation for Waveforms
Author
Mohammed Shurain
