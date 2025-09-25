# ALU & Sequential Circuit

## Overview
This project was developed as part of the **Logic Design (CSE111)** course.  
It consists of two phases:  

1. **Phase 1 – Combinational Circuit (ALU)**  
   - Designed a 4-bit Arithmetic Logic Unit (ALU) with two inputs (A and B).  
   - Implemented arithmetic and logical operations with ICs and simulated using Logisim.  

2. **Phase 2 – Sequential Circuit**  
   - Designed a sequential circuit using JK flip-flops and logic gates.  
   - The circuit counts the sequence `{1, 6, 0, 2, 7, 3, 4, 1}` repeatedly and displays it on a 7-segment display.  

Both circuits were implemented in hardware and validated with simulation tools.  

---

## Features
### Phase 1 – ALU
- 2 Arithmetic Operations:  
  - Addition (A + B) using **7483 (4-bit full adder)**  
  - Increment (A + 1) using **7483 with Cin = 1**  
- 2 Logical Operations:  
  - Bitwise AND using **7408**  
  - Bitwise OR using **7432**  
- Control truth table defined with DIP switches to select operation.  
- Output displayed on **7-segment display** using **7448 BCD to 7-segment decoder**.  

### Phase 2 – Sequential Circuit
- Implements a specific counting sequence `{1, 6, 0, 2, 7, 3, 4, 1}`.  
- Built with **7476 JK flip-flops**, **7486 XOR**, and **7432 OR gates**.  
- Clock generated with a **555 timer** configured for 1 Hz using calculated RC values.  
- Display on **7-segment display** with **7448 decoder**.  

---

## Technologies Used
- **Hardware ICs:** 7483, 7408, 7432, 74157, 7448, 7476, 7486, 555 Timer  
- **Logisim Simulator** for logic circuit design and testing  
- **Digital Logic Design principles** (combinational & sequential logic)  

---

## Skills Gained
- Designing and implementing combinational circuits (ALU)  
- Designing sequential circuits with flip-flops and state machines  
- Building and testing hardware using TTL ICs  
- Using **K-Maps** and **state diagrams** to derive equations  
- Interfacing with 7-segment displays  
- Clock generation and timing analysis with a 555 Timer  

---

## Getting Started
### Requirements
- Logisim (for simulation)  
- TTL ICs (as listed above)  
- Breadboard and power supply  
- 7-Segment display  

### Usage
1. Build the ALU circuit using the listed ICs or simulate in Logisim.  
2. Use DIP switches to select between operations (AND, OR, ADD, Increment).  
3. For the sequential circuit, wire the JK flip-flops, XOR, OR gates, and 555 timer as per design.  
4. Observe the counting sequence displayed on the 7-segment display.  

---

## Authors
- Ahmed Ehab Mohamed El-Baramony (21P0261)  
- Ahmed Mohamed Mohamed (22P0283)  
- Ahmed Mohamed Hassan El-Henawy (21P0298)  

