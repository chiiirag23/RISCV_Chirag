# Pipelined RISC-V Processor

A modular RISC-V processor implementation using Verilog HDL.

## Overview

This project contains Verilog modules for a RISC-V processor design.
The source files separate the processor's main components, including
instruction processing, control logic, arithmetic operations,
register storage, and memory interfaces.

## Design Modules

| File | Purpose |
|---|---|
| `RISCV.v` | Main processor module |
| `IF.v` | Instruction fetch |
| `ID.v` | Instruction decode |
| `Execute.v` | Execute stage |
| `Mem.v` | Memory-related logic |
| `writeback.v` | Write-back logic |
| `ALU.v` | Arithmetic logic unit |
| `ALU_dec.v` | ALU decoder |
| `Control.v` | Control logic |
| `main_decoder.v` | Main instruction decoder |
| `RegFile.v` | Register file |
| `Mem_Inst.v` | Instruction memory |
| `Data_mem.v` | Data memory |
| `memfile.hex` | Memory initialization file |

*Module descriptions are based on filenames and should be
confirmed against the source code.*

## Tools

- Verilog HDL
- Simulation tool: [Add the tool you actually used]

## Verification

[Describe the testbench, instructions tested, and simulation results
after running the design.]

## Future Improvements

- Develop a testbench for supported instructions.
- Verify processor behaviour through simulation.
- Document supported instructions and any design limitations.
- Explore FPGA implementation.

## Attribution and License

[Identify the original source, applicable license, and your
contributions. Retain required notices and attribution.]