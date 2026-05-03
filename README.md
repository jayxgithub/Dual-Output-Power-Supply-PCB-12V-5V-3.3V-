
# ⚡ Dual Output Power Supply PCB (12V → 5V & 3.3V)

## 📌 Project Overview

This project is a **custom-designed PCB power supply module** created using **KiCad**, which efficiently converts a **12V DC input** into **regulated 5V and 3.3V outputs**.

It is designed for use in **embedded systems, IoT devices, and microcontroller-based projects** where stable dual voltage rails are required.

---

## 🎯 Key Features

* 🔋 Converts **12V DC → 5V & 3.3V**
* ⚙️ Uses **linear voltage regulators (LD1117 series)**
* 🛡️ Includes **input protection using fuses**
* 💡 LED indicators for power status
* 🔌 Multiple terminal connectors for easy interfacing
* 🧩 4 Layer PCB Design

---

## 🛠️ Tools & Technologies

* **KiCad** (Schematic + PCB Design)
* **PCB Layout Design**
* **Electronic Components (Through-hole + SMD)**
* **Basic Power Electronics Concepts**

---

## ⚙️ Working Principle

1. **Input Stage**

   * 12V DC is supplied through connectors.
   * Fuses provide protection against overcurrent.

2. **Voltage Regulation**

   * **LD1117S50** → Regulates 12V to **5V**
   * **LD1117S33** → Regulates 12V to **3.3V**

3. **Filtering**

   * Capacitors remove noise and stabilize voltage.

4. **Indication**

   * LEDs indicate power presence on outputs.

---

## 📂 Repository Structure

```
📁 Dual-Power-Supply-PCB
│── 📄 power supply.kicad_pro      # Project file
│── 📄 power supply.kicad_sch      # Schematic
│── 📄 power supply.kicad_pcb      # PCB layout
│── 📄 BOM.csv                     # Components list
│── 📁 images/                     # PCB screenshots (top/bottom/3D)
│── 📄 README.md                   # Project documentation
```

---

## 📋 Bill of Materials (BOM)

| Id | Designator     | Footprint                             | Qty | Value/Designation  |
| -- | -------------- | ------------------------------------- | --- | ------------------ |
| 1  | F4, F1, F2, F3 | Fuseholder_TR5_Littelfuse_No560_No460 | 4   | Fuse_Small         |
| 2  | R1, R2, R3, R4 | R_1206_3216Metric                     | 4   | 1k                 |
| 3  | C1, C2         | C_1206_3216Metric                     | 2   | 10µF               |
| 4  | C3, C4         | C_1206_3216Metric                     | 2   | 100nF              |
| 5  | C5, C6         | C_1206_3216Metric                     | 2   | 10nF               |
| 6  | C7, C8         | C_1206_3216Metric                     | 2   | 0.1µF              |
| 7  | D1, D2         | LED_D5.0mm                            | 2   | LED Indicator      |
| 8  | J1, J2, J3, J4 | Altech_AK300_1x02_P5.00mm_45-Degree   | 4   | Terminal Block     |
| 9  | SW1, SW2       | SW_DIP_SPSTx01_Piano                  | 2   | Switch             |
| 10 | U1             | SOT-223-3_TabPin2                     | 1   | LD1117S50TR (5V)   |
| 11 | U2             | SOT-223-3_TabPin2                     | 1   | LD1117S33TR (3.3V) |
| 12 | Q1, Q2         | TO-92_Inline                          | 2   | 2N3904             |

---

## 🔍 Design Highlights

* Proper **decoupling capacitor placement** near regulators
* **Wide traces for power lines** to handle current safely
* Clean and organized **component placement**
* Easy-to-understand schematic for learning purposes

---

## 🚀 Applications

* Microcontroller projects (Arduino, ESP32, STM32)
* IoT systems
* Embedded hardware prototypes
* Educational electronics labs

---

## 📸 Preview (Add Screenshots)

> Add images here after uploading:

* PCB Top View
* PCB Bottom View
* 3D View

---

## 📚 Learning Outcomes

* PCB design using KiCad
* Voltage regulation concepts
* Component selection and placement
* Real-world hardware debugging understanding

---

## 👨‍🎓 About Me

I am a **final-year Electronics & Telecommunication Engineering student** passionate about:

* PCB Design
* Embedded Systems
* Python & Automation

This project reflects my hands-on experience in **hardware design and practical electronics**.

---

## ⭐ Future Improvements

* Add **switching regulator (buck converter)** for higher efficiency
* Include **thermal analysis**
* Add **current limiting and protection circuits**
* Compact multilayer PCB design

---

## 🙌 If you like this project

Give it a ⭐ on GitHub and feel free to fork or improve it!

