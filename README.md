# Logic-Controlled Board – Final Project  
**Course:** COE322 – Logic Design Lab  
**Institution:** Lebanese American University  
**Date:** 14/05/2025  

## Team Members
- Mahmoud Al Ashkar — 202302853  
- Hussein Itani — 202300351  
- Mahdi Zein Al Dine — 202300041  

---

## 📘 Overview
This project demonstrates a **Logic-Controlled Board** that uses digital logic design, finite state machines (FSM), and memory elements to dynamically control a set of four colored LEDs (red, green, blue, yellow) using four switches.

The behavior changes based on the last switch turned off, and the mapping between switches and LEDs is retained even when switch caps are physically swapped, creating the illusion of "intelligent" control.

---

## 🔧 Features
- **Dynamic LED Control** based on last switch turned off  
- **Locked Mode** for direct mapping  
- **Capless Switch Trick** to deactivate switches  
- **7-Segment Display** to indicate mode  
- **Fully implemented FSM, Sequence, and Mapping Units**  
- **Custom 100 kHz Clock using NE555**  
- **RC-based Reset Timer** when all LEDs are off  
- **Breadboard and PCB Implementation**  
- **Soldered Components with Replaceable IC Sockets**  

---

## 🧰 Components Used
- 4 Toggle Switches with Colored Caps  
- 4 Colored LEDs  
- 1 Circuit Board & Breadboard  
- NE555 Timer IC  
- 74LS Series Logic ICs (Flip-flops, Adders, Multiplexers, Decoders, Gates)  
- 7-Segment Display  
- Assorted Resistors, Capacitors, Wires  
- Quartus II & LTSpice software  

(Full component list provided in the report.)

---

## 📐 Key Modules
- **Finite State Machine (FSM):** Controls dynamic behavior based on switch sequence  
- **Mapping Unit & Memory:** Stores switch-to-LED mapping  
- **Display Unit:** Drives 7-segment mode display  
- **Enable Memory:** Controls when switches can remap  
- **Timers & Clocks:** Custom 100 kHz oscillator and frequency dividers  

---

## 🛠 Implementation
- Simulated on **Quartus II**  
- Clock circuit simulated on **LTSpice**  
- Physically implemented using **breadboard** and **soldered board**  
- Modular design for easier debugging and IC replacement  

---

## ⚡ Power & Timing
- 100 kHz base clock using NE555  
- Frequency divider produces 12.5 kHz signal  
- Reset logic based on NOR gate + RC timing  

---

## 🧪 Challenges Faced
- Clock delay propagation  
- Soldering difficulties and IC faults  
- Tight layout spacing  
- Resolved using modular wiring, IC sockets, and frequency tuning  

---

## ✅ Outcomes
- Fully functional dynamic LED control board  
- Accurate state-based behavior  
- Visually engaging and educational for demonstrating FSMs and digital logic  

---

## 📄 Report
The full technical report, schematics, and analysis are available in `FinalReport.pdf`.

