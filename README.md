# 555 Timer “Hello World” PCB

This project is a simple **555 timer astable oscillator**, designed as my **first PCB**.  
The goal was to go through the complete workflow: schematic capture, PCB layout, and design rule checks using **Altium Designer 26.1.1**.

The circuit generates a low-frequency square wave (≈1 Hz), suitable for driving an LED or acting as a basic clock signal.

---

## Overview

- **IC:** NE555 timer
- **Configuration:** Astable mode
- **Supply Voltage:** 5 V
- **Output:** Square wave (~1 Hz), 
- **EDA Tool:** Altium Designer 26.1.1

This is a classic “Hello World” electronics project, used to learn fundamentals of PCB design.

---

## What I Learned

- Creating and organizing a schematic in Altium
- Understanding nets, junctions, and net labels
- Connecting multiple pins to the same node correctly
- PCB layout basics:
  - Routing traces
  - Using vias and layers
  - Avoiding shorts between different nets
- Running ERC and DRC checks
- Preparing a design suitable for manufacturing

---

## Files Included

- **Schematic:** `.SchDoc`
- **PCB Layout:** `.PcbDoc`
- **Images:** <img width="943" height="489" alt="Screenshot 2026-01-25 233512" src="https://github.com/user-attachments/assets/d591b855-006a-44c6-80fd-50daadb016bb" />
<img width="796" height="500" alt="Screenshot 2026-01-25 225857" src="https://github.com/user-attachments/assets/10b0f388-ee38-4d21-9ce6-a419565628a2" />

---

## Notes

This project was intentionally kept simple to focus on **correct workflow and fundamentals** rather than complexity.  
Future revisions could include:
- Adjustable frequency (potentiometer)
- LED driver stage
- Power filtering improvements
- Smaller board size or SMT components
The decoupling capacitor was intentionally placed close to the IC power pins (VCC and GND) to minimize loop area and reduce supply noise.

---

