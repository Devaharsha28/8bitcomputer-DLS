# 8-Bit Computer Specifications

## Functionality
- Inspired by microcontroller design, providing programmable control, arithmetic operations, and input/output capabilities.

## Data Paths
- **8-bit Data Bus**: Transfers data between the CPU, memory, and peripherals.
- **8-bit Address Bus**: Addresses up to 256 bytes of memory.

## Architecture
 - **Harvard Architecture**: Separate memory spaces for program instructions and data, allowing simultaneous access to both.
 - **Minimal Instruction Set Computing (MISC)**: The CPU is designed with a minimal instruction set, currently supporting 22 instructions.
 - **Accumulator-Based CPU**: All operations are performed through a central accumulator register.
 - **All Instructions Are 2 Bytes**: Each instruction is 16 bits (2 bytes) wide.

## Functionality
 - Inspired by microcontroller design, providing programmable control, arithmetic operations, and input/output capabilities.

## Data Paths
 - **8-bit Data Bus**: Transfers data between the CPU, memory, and peripherals.
 - **8-bit Address Bus**: Addresses up to 256 bytes of memory.
 - **Program Memory**: Utilizes a 256x16 ROM for instruction storage, supporting up to 256 instructions, each 16 bits wide.

## Chip Library
 - Logic Gates: AND, OR, NOT, NOR, XOR, XNOR
 - Flip-Flops: D FF, JK FF, SR FF, T FF, SR LATCH, 8d-ff
 - Registers: register, GPRs
 - Counters: 8B-COUNTER, 8BCOUNTER-IB
 - Multiplexers/Demultiplexers: 2-4DEMUX, 4-16 DEMUX, 4-1mux-no-enable
 - ALU: Arithmetic and Logic Unit, 8b adder, complementer
 - Display: 7segdisplay, 7seg-driver-hex

## ALU
 - Supports arithmetic and logic operations
 - Control signals: AU/LU, add'/sub, LU-s1, LU-s0
 - Outputs: OUT (8-bit), carry, isZero, isNegative

## Registers & Memory
 - General Purpose Registers (GPRs) for data storage
 - register chip for state retention

## Project Details
 - Built in Digital Logic Sim (DLS) v2.1.6
 - Creation date: 2026-01-25
 - Last saved: 2026-02-25

## Instruction Set
 - Minimal Instruction Set Computing (MISC) with 22 instructions
 - All instructions are 2 bytes (16 bits)

## Chips Implemented
The following chips are implemented in the Chips/ directory:
 - 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, a, b, c, d, e, f
 - AND, OR, NOR, NOT, XOR, XNOR
 - D FF, JK FF, SR FF, SR LATCH, T FF, 8d-ff
 - register, GPRs
 - 8B-COUNTER, 8BCOUNTER-IB
 - 2-4DEMUX, 4-16 DEMUX, 4-1mux-no-enable
 - 7seg-driver-hex, 7segdisplay
 - 14or, 16or, 3i-AND, C1, RISE EDGE DETECTOR
 - 8b 3statebuffer, 8b adder, ALU, Arithmetic unit, Logic Unit, PROGRAM COUNTER, complementer, exp2, full adder, half-adder, idk, isZero, jmp func pc, one, test, 5-32 mux, 6-64 mux, 16and, 16xor