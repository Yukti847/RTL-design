4-bit Single-Port RAM Design (Verilog)
Project Overview
This project implements a 4-bit wide Single-Port RAM using Verilog with:
Synchronous read/write operations
Asynchronous reset
Basic testbench for verification
The design focuses on understanding memory architecture, sequential logic, and address-based data access in VLSI systems.
Objectives
Design a Single-Port RAM

Implement synchronous read/write

Implement asynchronous reset

Verify functionality using testbench

Understand memory fundamentals in VLSI

Specifications
Parameter	Value
Data Width	4 bits
Memory Depth	4 locations
Address Width	2 bits
Port Type	Single Port
Functional Description
 Write Operation
Occurs on positive edge of clock

Enabled when we = 1

Data (wdata) is written to address (addr)

 Read Operation
Synchronous read

Output (rdata) updates on clock edge

Occurs when we = 0

 Reset Operation
Asynchronous reset (rst)

Clears all memory locations to 0

Immediate effect (independent of clock)

 Simulation Output
Write data stored correctly at given addresses

Read data matches expected values

Reset clears all memory

 Features Implemented
 Synchronous read/write
 Asynchronous reset
 Address-based memory access
 Clock-driven operation
 Basic verification using testbench
