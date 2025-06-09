## Solar-Powered | ESP32-Based | Environmental Monitoring

A compact, modular, and field-deployable IoT node designed for solar-powered environmental monitoring. The system uses the MCP73871 for intelligent power path management between USB, solar, and LiPo battery sources. Designed in Altium Designer, this project showcases low-power design, modular sensor interfaces, and real-world PCB engineering for IoT applications.

## 🚀 Project Objectives
✅ Design a professional-grade PCB in Altium Designer

✅ Learn and apply low-power and energy-harvesting design techniques

✅ Implement plug-and-play I²C sensor modularity

✅ Create a clean, well-documented project suitable for portfolio and collaboration

## ⚡ Power Architecture

MCP73871 handles simultaneous USB and solar charging, with:

Power-path management between input, battery, and system load

Autonomous selection of input source (USB or solar)

Battery charging with thermal regulation

Status monitoring (charging, power source, fault)

3.7V LiPo battery with system regulated to 3.3V via AP2112K LDO

Battery voltage monitoring via voltage divider + ADC input

ESP32 deep sleep modes used to optimize power draw

## 🧠 Core Components
Component	Description
ESP32-WROOM	MCU with integrated Wi-Fi + BLE
BME280	Temperature, humidity, pressure sensor
TSL2561	Ambient light sensor (Lux)
CCS811	Air quality sensor (eCO₂ & TVOC)
PIR Sensor	Motion detection
AP2112K	3.3V Low Dropout Regulator
MCP73871	Smart battery charger with power-path

## 🛠️ Project Status
Task	Status
✅ Schematic design (Altium)	Completed
✅ PCB layout (Altium)	Finalized
✅ Sensor integration	Completed
🔄 Firmware development	In progress
🔄 Power testing & tuning	In progress
📝 Documentation	Ongoing

## 🔧 Tools & Resources
Altium Designer – Schematic and PCB layout

Arduino IDE – Firmware development (ESP32 core)

Multimeter, DC supply – Hardware validation

Datasheets + Reference designs – Component integration

## 📘 Learning Outcomes
Through this project, I’ve explored:

Smart LiPo charging + power management (MCP73871)

Deep sleep strategies on ESP32

Clean and compact PCB routing for sensor-based systems

Building modular I²C headers for sensor extensibility

Real-world prototyping, debugging, and documentation
