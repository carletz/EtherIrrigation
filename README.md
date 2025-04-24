# 💧 EtherIrrigation - Another Irrigation Controller – 2025
This project is an electronic system designed for **automated irrigation control**. It integrates input sensors, logic control, and power output sections to manage valves and environmental readings efficiently.
The aim of this project is to have an ehternet controller into my garden. WiFi wasn't available so I decided to redesign it starting from other projects found on the net.
The design is based on this dimension because I put everything inside a 4 DIN module box desiged by me and 3D printed. Probably everything can be redesigned on a single board and rebuild with the same effectiveness.
---

## 🧩 Project Structure

The system is divided into three main sections:

1. **Input (V2.2)**  
   Handles all digital and analog inputs, including:
   - Manual lever input switch

2. **Control (V2.4)**  
   Microcontroller-based logic and connectivity:
   - ESP32
   - WiFi or Ethernet communication
   - Firmware updatable
   - Temperature sensors pins available (DS18B20)

3. **Power (V2.4)**  
   Power switching and protection section:
   - MOSFETs to drive solenoids
   - Surge protection and fuse circuits
   - Isolated DC/DC converters

---

## 📐 Schematics

All schematics are included in PDF format:

- [`SCH_Input V2.2_2025-04-24.pdf`](SCH_Input%20V2.2_2025-04-24.pdf)
- [`SCH_Controllo V2.4_2025-04-24.pdf`](SCH_Controllo%20V2.4_2025-04-24.pdf)
- [`SCH_Potenza V2.4_2025-04-24.pdf`](SCH_Potenza%20V2.4_2025-04-24.pdf)

These documents describe all circuit sections in detail. Each sheet includes reference designators and functional labels.

---

## ⚙️ Features

- Modular design: Input / Control / Power separated
- Easy to scale and adapt to new sensors or actuators
- Built-in protection: ESD, overcurrent, reverse polarity
- Supports manual or fully automatic modes

---

## 🚀 Getting Started

1. Review all schematics to understand pin mapping and power routing.
2. Assemble the circuits section by section.
3. Flash the firmware to the microcontroller (I used ESPHome for this project).
4. Connect sensors and actuators according to the schematics.

---

## 🛠 BOM and Production

A full production package (Gerber files, BOM, 3D renderings) are included.

---

## 🧠 Notes

- Always test with current-limited power supplies during prototyping.
- Use waterproof enclosures if deployed outdoors.

---

## 📅 Version

- Input schematic: V2.2 (April 2025)
- Control schematic: V2.4 (April 2025)
- Power schematic: V2.4 (April 2025)

Created with **EasyEDA**.

---
