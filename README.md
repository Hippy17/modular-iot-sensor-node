# modular-iot-sensor-node
Modular IoT node with solar-powered LiPo battery, ESP32, and environmental sensors
 Modular IoT Sensor Node  
**Solar-Powered | ESP32-Based | Environmental Monitoring**

This is a personal hardware design project aimed at building a compact, solar-powered, low-power IoT node for environmental sensing. Designed in **Altium Designer**, the node is modular, field-deployable, and built around the ESP32, capable of running on solar energy with LiPo battery backup.

---

## Project Goals

- ✅ Build a **professional-grade PCB** in Altium Designer
- ✅ Learn to design for **low-power and renewable energy use**
- ✅ Enable modular plug-and-play **sensor support (I²C)**
- ✅ Document the project thoroughly for my **portfolio & GitHub**

---

## Power Architecture

The device uses a hybrid power design:
- **Solar charging** via CN3065
- **USB charging & protection** via TP4056
- **3.7V LiPo battery** with 3.3V LDO regulation (AP2112K)
- Battery voltage monitored via ADC
- Designed for **deep sleep** to extend runtime

---

## Core Components

| Component     | Description                              |
|---------------|------------------------------------------|
| **ESP32-WROOM** | Main MCU with Wi-Fi + BLE               |
| **BME280**     | Temp, humidity, and pressure sensor     |
| **TSL2561**    | Light intensity sensor (Lux)            |
| **CCS811**     | Air quality sensor (eCO₂ & TVOC)        |
| **PIR**        | Motion detection                        |
| **AP2112K**    | 3.3V LDO Regulator                      |
| **CN3065**     | Solar Li-ion battery charger            |
| **TP4056**     | USB charging + protection               |

---

## Project Status

| Task                        | Status          |
|-----------------------------|-----------------|
| Altium schematic design     | 🟡 In progress  |
| PCB layout                  | 🔜 Coming soon  |
| Firmware testing            | 🔜 Coming soon  |
| Sleep current optimization  | 🔜 Coming soon  |
| GitHub documentation        | 🟡 Ongoing      |

---

## Tools Used

- **Altium Designer** (schematic + PCB design)
- **ESP32 + Arduino IDE**
- **DC bench supply + multimeter** for testing
- **Datasheets + application notes** for all ICs

---

## What I'm Learning

This project is part of my self-driven learning path to become a better hardware engineer. Through it, I'm gaining hands-on experience in:

- LiPo charging and protection circuits
- Efficient power rail design
- Sensor interfacing and PCB routing
- Sleep modes and power budgeting
- Documenting real-world hardware projects

---

## Let's Collaborate or Talk

I’m always happy to connect with other makers, engineers, and potential collaborators. If you’re interested in:

- Reviewing the schematics
- Suggesting improvements
- Forking the project or adapting it
- Offering feedback on documentation or layout

Feel free to open an issue or reach out!

---
