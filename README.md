# tang-nano-9k-2to1-mux
Beginner Verilog HDL project implementing a 2:1 multiplexer on the Sipeed Tang Nano 9K FPGA, with pin constraints and a real-hardware demonstration.
# 2:1 Multiplexer on Tang Nano 9K

## Overview
This project implements a 2:1 multiplexer using Verilog HDL on the Sipeed Tang Nano 9K FPGA development board.

## Boolean Expression
`y = (~s & a) | (s & b)`

## Files
- `mux_2to1.v` — Verilog implementation using an `always @(*)` block and `case` statement.
- `mux_2to1.cst` — Pin assignments and I/O configuration for the FPGA.
- `demo.mp4` — Video demonstrating the design running on physical FPGA hardware.

## What I Learned
- Combinational logic design using Verilog.
- Writing and understanding a 2:1 multiplexer.
- FPGA pin mapping and constraint files.
- Programming and testing a design on real hardware.

## Testing
The hardware demonstration verifies the button-controlled LED behavior. The select input was held LOW, so the `a` input path was tested; switching between both data inputs remains future work.
