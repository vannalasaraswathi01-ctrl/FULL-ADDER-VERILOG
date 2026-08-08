# Full Adder using Verilog

## Description

This project implements a **1-bit Full Adder** using Verilog HDL.

A Full Adder adds three 1-bit inputs:

* A
* B
* Cin (Carry-in)

It produces two outputs:

* Sum
* Cout (Carry-out)

## Logic Equations

**Sum = A ⊕ B ⊕ Cin**

**Cout = AB + BCin + ACin**

## Files

* `full_adder.v` – Full Adder Verilog design
* `full_adder_tb.v` – Testbench for simulation
* `README.md` – Project documentation

## Truth Table

| A | B | Cin | Sum | Cout |
| - | - | --- | --- | ---- |
| 0 | 0 | 0   | 0   | 0    |
| 0 | 0 | 1   | 1   | 0    |
| 0 | 1 | 0   | 1   | 0    |
| 0 | 1 | 1   | 0   | 1    |
| 1 | 0 | 0   | 1   | 0    |
| 1 | 0 | 1   | 0   | 1    |
| 1 | 1 | 0   | 0   | 1    |
| 1 | 1 | 1   | 1   | 1    |

## Simulation

The testbench checks all **8 possible input combinations** and displays the Sum and Carry outputs.

## Tools Used

* Verilog HDL
* VS Code
* Icarus Verilog
* GTKWave
* GitHub

## Author

Divya
