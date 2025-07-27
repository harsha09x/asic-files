<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This project implements a simplified MIPS32 processor using Verilog. It supports basic R-type, I-type, and load/store instructions. The design includes modules for instruction fetch, decode, ALU execution, memory access, and write-back stages, working in a pipelined or single-cycle architecture depending on your setup. Each instruction is executed according to MIPS32 standards, processing 32-bit data and using a register file of 32 registers.
## How to test

To test the project:

1.Write a MIPS32 assembly program and convert it to machine code.
2.Load the machine code into the instruction memory.
3.Run the simulation using a testbench.
4.Observe register values and memory outputs in the simulation waveform (e.g. using GTKWave).
5.Verify that the output matches expected results for each instruction executed.

## External hardware

No external hardware is used in this project. It is a fully simulated design tested using software tools like ModelSim, Vivado, or GTKWave. However, optional hardware extensions like 7-segment displays, LEDs, or PMODs can be added for visualization
