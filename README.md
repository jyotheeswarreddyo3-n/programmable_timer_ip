# programmable_timer_ip
FPGA-based programmable timer IP in Verilog with interrupt generation and waveform simulation in Xilinx Vivado.
# Programmable Timer IP using Verilog

## Overview

This project implements a configurable programmable timer IP core using Verilog HDL in Xilinx Vivado.

The timer generates interrupt signals after a programmable delay using:
- clock divider
- synchronous counter
- comparator logic
- interrupt generation


## Features

- Programmable timer interval
- Interrupt pulse generation
- Clock division
- Synchronous design
- FPGA synthesizable RTL
- Vivado simulation support


## Architecture

Clock → Clock Divider → Counter → Comparator → Interrupt Logic


## Files

| File | Description |
|---|---|
| programmable_timer.v | Main timer RTL |
| programmable_timer_tb.v | Testbench |
| timer_waveform.png | Simulation waveform |


## Simulation

Simulated using:
- Xilinx Vivado
- Verilog HDL


## Waveform

Interrupt is generated when:

counter == load_value


## Applications

- Embedded systems
- UART baud timing
- SPI scheduling
- Real-time systems
- Interrupt-driven architectures


## Future Improvements

- Auto reload timer
- AXI Lite interface
- PWM mode
- Multi-channel timer
- Interrupt status registers


## Author

Jyotheeswar Reddy
