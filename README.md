# Smart Street Light

---

## 📌 Project Overview

**Project Name:** Smart Street Light  
**Theme:** IoT-based Automation System  

- The Smart Street Light project is an IoT-based automation system designed to reduce energy consumption by intelligently controlling street lights using sensors. The system automatically turns ON or OFF LED lights based on ambient light levels and object detection.

> This project is built using the Arduino Uno microcontroller and programmed using the Arduino IDE (C/C++ based).

---

## 🎯 Objective

- To automate street lighting using sensors.
- To reduce electricity wastage.
- To improve energy efficiency.
- To demonstrate practical IoT implementation using Arduino.

---

## 🛠️ Components Used

| Component | Quantity |
|-----------|----------|
| Arduino Uno Board | 1 |
| IR Sensors | 3 |
| LDR Sensors | 3 |
| LED Lights | 3 |
| Male-to-Male Jumper Wires | 10 |
| Male-to-Female Jumper Wires | 10 |
| Cardboards (for model structure) | As required |
| USB Cable (for programming) | 1 |
| Arduino IDE | Software |

---

## 🧠 Working Principle

The Smart Street Light system works based on two main conditions:

### 1️⃣ Light Detection (LDR)
- LDR (Light Dependent Resistor) detects ambient light.
- If it is daytime → Lights remain OFF.
- If it is nighttime → System activates LED control.

### 2️⃣ Object Detection (IR Sensors)
- IR sensors detect movement (vehicle/pedestrian).
- When an object is detected:
  - Corresponding LED turns ON.
- When no object is detected:
  - LED remains OFF to save power.

This ensures lights operate only when needed.

---

## 🔌 System Architecture

LDR         → Detects Day/Night  
IR Sensors  → Detects Motion  
Arduino Uno → Processes sensor input  
LEDs        → Output (Street Lights)

---

## 🔄 Workflow

1. System powers ON.
2. LDR checks ambient light level.
3. If light level is low (night):
   - IR sensors are activated.
4. If IR sensor detects motion:
   - Corresponding LED turns ON.
5. After motion stops:
   - LED turns OFF after delay.
6. During daytime:
   - All LEDs remain OFF.

---

## 💻 Software Used

- **Arduino IDE**
- Programming Language: C/C++ (Arduino-based)

---

## ⭐ Support  

> If this repository helps you, please consider giving it a ⭐ on GitHub—it motivates future updates!

---

## 👨‍💻 AUTHOR 

### Vinaal R

Passionate Learner | Creative Developer | Coding Enthusiast

- Always exploring. Always building. Always improving.
- I learn by building. I grow by experimenting.
- Coding isn’t just a skill for me — it’s a craft I’m shaping every single day.

### Contact me through 

<div align="center">
  <a href="https://vinaalr.netlify.app/">
  <img src="https://img.shields.io/badge/VR%20-%20Portfolio-d5d5d5?style=for-the-badge&labelColor=0A0209&color=d5d5d5&logoColor=0A0209" />
</a>
<a href="https://www.linkedin.com/in/vinaal/">
  <img src="https://img.shields.io/badge/LinkedIn-d5d5d5?style=for-the-badge&logo=linkedin&logoColor=0A0209" alt="LinkedIn" />
</a>
<a href="https://github.com/Dark-Vinaal">
  <img src="https://img.shields.io/badge/GitHub-d5d5d5?style=for-the-badge&logo=github&logoColor=0A0209" alt="GitHub" />
</a>
<a href="https://linktr.ee/Darkxzz999">
  <img src="https://img.shields.io/badge/Linktree-d5d5d5?style=for-the-badge&logo=linktree&logoColor=0A0209" alt="Linktree" />
</a>
</div>

---
