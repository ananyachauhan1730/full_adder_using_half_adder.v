# full_adder_using_half_adder.v
Verilog HDL implementation of a Full Adder using two Half Adders, designed and simulated using Xilinx Vivado.
# Full Adder Using Half Adder – Verilog HDL

This project implements a **Full Adder** using **two Half Adders** in **Verilog HDL**.

## Description
The Full Adder is designed by cascading two Half Adder modules.  
The carry output is generated using an OR gate.  
This design follows a modular and reusable approach.

## Files Included
- `half_adder.v` – Verilog code for Half Adder
- `full_adder_using_half_adder.v` – Verilog code for Full Adder using Half Adders

## Tool Used
- Xilinx Vivado

## Functionality
- Inputs: `a`, `b`, `cin`
- Outputs: `sum`, `carry`

## Learning Outcome
- Understanding hierarchical design in Verilog
- Using multiple modules in a single design
- Basic digital logic implementation

## Author
Ananya Chauhan
