# Implementation Report

## Number of Chips Implemented
We have implemented a total of **42 chips** in the Chips/ directory.

## Chip Categories
- **Logic Gates** (6): AND, OR, NOR, NOT, XOR, XNOR
- **Sequential Elements** (6): D FF, JK FF, SR FF, SR LATCH, T FF, 8d-ff
- **Registers** (2): register, GPRs
- **Counters** (2): 8B-COUNTER, 8BCOUNTER-IB
- **Multiplexers/Demultiplexers** (3): 2-4DEMUX, 4-16 DEMUX, 4-1mux-no-enable
- **Display Components** (2): 7seg-driver-hex, 7segdisplay
- **Other Logic** (5): 14or, 16or, 3i-AND, C1, RISE EDGE DETECTOR
- **Digit Chips** (16): 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, a, b, c, d, e, f

## Progress Towards 8-Bit Computer
The implemented chips cover essential components for building an 8-bit computer:
- Basic logic operations are supported by the gates.
- Memory and state storage is provided by flip-flops, latches, registers, and counters.
- Data routing is handled by multiplexers and demultiplexers.
- Output capabilities include 7-segment displays for visualization.

This forms a solid foundation for constructing an ALU, control unit, memory interface, and I/O systems. The project is in progress, with ongoing work to integrate these components into a functional 8-bit CPU architecture.