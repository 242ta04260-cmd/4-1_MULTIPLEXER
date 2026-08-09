# 4x1 Multiplexer in Verilog

This project implements a 4-to-1 Multiplexer using Verilog HDL.

## Inputs

- I[3:0] - Four data inputs
- S[1:0] - Two select inputs

## Output

- Y - Selected output

## Selection Table

| S1 | S0 | Output |
|----|----|--------|
| 0  | 0  | I0     |
| 0  | 1  | I1     |
| 1  | 0  | I2     |
| 1  | 1  | I3     |

## Files

- `mux4to1.v` - 4x1 Multiplexer design
- `mux4to1_tb.v` - Testbench for simulation

## Tools

- Verilog HDL
- Visual Studio Code
- Icarus Verilog / Vivado / ModelSim
