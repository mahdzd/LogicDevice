# Logic-Controlled Board – Digital Logic Design Project

> **Course**: COE211 – Logic Design  
> **University**: Lebanese American University – Spring 2025  
> **Team**: Mahdi Zein Al Dine, [Other Team Members]  
> **Instructor**: Leila Issa

---

## 📘 Project Overview

The Logic-Controlled Board is an interactive switching system featuring four toggle switches and four colored LEDs (Red, Green, Blue, Yellow). Each switch dynamically maps to an LED based on the **last switch turned off**, allowing for an illusion of smart behavior.

Special functionality includes:
- Sequence-dependent LED activation (4 unique sequences)
- Switch caps that disable functionality when removed
- A reset timer
- Optional "practice mode" with a 7-segment display showing the active sequence
- Lock/unlock mode via startup logic

---

## 🔩 Features

- ✅ FSM-controlled dynamic switch-LED mapping  
- ✅ 7-segment display mode (practice/performance toggle)  
- ✅ Capless switch detection and timer-based disabling  
- ✅ Sequence memory and reset logic  
- ✅ Clean circuit design with minimal IC usage  

---

## 🔧 Tools & Components

| Tool/Component     | Description                          |
|--------------------|--------------------------------------|
| **Quartus II**     | Digital design and simulation        |
| **7448 IC**         | BCD to 7-segment decoder (active high) |
| **555 Timer**      | Clock signal generator               |
| **Toggle Switches**| 4 physical user inputs               |
| **LEDs**           | Red, Green, Blue, Yellow             |
| **Breadboard**     | Physical assembly                    |

---

## 💻 Files Included

- `logic_control.qsf` – Quartus project file  
- `fsm_control.bdf` – FSM design (Block Diagram)  
- `mapping_logic.v` – Verilog implementation  
- `report.pdf` – Full documentation  
- `README.md` – This file  
- `sequence_demo.gif` – (Optional) waveform or simulation visual  

---

## 📺 Demo Video

[![Watch Demo](https://img.youtube.com/vi/your_video_id/0.jpg)](https://youtu.be/your_video_id)  
> _Click above to watch the full project demo._

---

## 🧠 Learning Outcomes

- Practical application of Boolean algebra and FSMs  
- Optimization techniques (gate reduction, Karnaugh maps)  
- Troubleshooting real hardware bugs  
- Soldering and hardware implementation  
- Team collaboration and documentation

---

## 📦 How to Run (Simulation)

1. Open `logic_control.qsf` in **Quartus II**
2. Compile the project
3. Launch Simulation → RTL Simulation
4. Observe FSM behavior and LED output

---

## 📜 License

This project is for academic use only under LAU's academic integrity policy.  
© 2025, Team Mahdi Zein Al Dine.

