# Wiper-Auto-ON-System-Simulation-using-CAN-Messages
Description: This project simulates an automotive feature where: - Rain Sensor detects rain intensity - BCM ECU decides whether to turn Wipers ON/OFF - Actuator (Wiper Motor) executes the command
# 🚗 Automotive Features Simulation (Python)

This repository contains **Python simulations of automotive features** using CAN message flow.
Good for **learning & testing ECU-Sensor-Actuator systems**.

---

## 📌 Implemented Features
1. **Headlamp Auto ON System**
   - Sensor: Ambient Light
   - ECU: BCM
   - Actuator: Headlamp Relay

2. **Wiper Auto ON System**
   - Sensor: Rain Sensor
   - ECU: BCM
   - Actuator: Wiper Motor

---

## 🔧 CAN Message IDs
| Feature          | Sensor ID | ECU/Actuator ID |
|------------------|-----------|-----------------|
| Headlamp Auto ON | 0x101     | 0x201           |
| Wiper Auto ON    | 0x102     | 0x202           |

---

## 🚀 Skills Demonstrated
- Understanding of **Sensors, ECUs, Actuators**
- **CAN IDs and priority**
- **Tester validation (Pass/Fail checks)**
- **Python simulation & clean coding**
- Practical automotive project structure

