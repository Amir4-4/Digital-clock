# Digital-clock  
#  Multi-Digit BCD Counter Project

##  Project Overview
This project is a multi-digit digital counter and digital clock system designed using digital logic circuits. It demonstrates how binary coded decimal (BCD) counters, logic gates, and 7-segment displays work together to simulate real-world time counting systems such as clocks and stopwatches.

---

##  System Description
The circuit is built using multiple identical digit blocks, where each block represents one decimal digit (0–9). Each digit consists of:

- BCD Counter (4-bit)
- Reset and Carry Logic
- BCD to 7-Segment Decoder
- 7-Segment Display

---

##  How It Works

### 1. Clock Input
- A pulse generator (e.g., 1 Hz clock using 555 timer)
- Each pulse increments the counter by 1

---

### 2. BCD Counter
- Counts from 0000 (0) to 1001 (9)
- After 9, it resets to 0 and sends a carry to the next digit

---

### 3. Reset & Carry Logic
- Detects when output = 9 (1001)
- Resets current digit
- Sends carry to next digit using logic gates

RESET condition:
A · D · B' · C'

---

### 4. BCD to 7-Segment Decoder
- Converts 4-bit binary input into 7 signals (a–g)
- Drives the 7-segment display

---

### 5. 7-Segment Display
- Displays decimal digits 0–9
- Controlled via current-limiting resistors

---

## Concepts Used
- BCD Number System
- Logic Gates (AND, OR, NOT)
- Karnaugh Map Simplification
- Combinational Logic Design
- Sequential Circuits (Counters)
- Digital Display Interfacing

---

##  Clock System Extension
The system can be extended to:

- Seconds counter (0–59)
- Minutes counter (0–59)
- Hours counter (12/24 format)
- Stopwatch mode
- Alarm system using comparators (e.g. 74LS85)

---


##  Conclusion
This project demonstrates a complete digital clock system using fundamental digital electronics concepts. It combines counters, decoders, and logic gates to simulate real-time counting behavior, similar to real-world digital clocks and stopwatches.

---
