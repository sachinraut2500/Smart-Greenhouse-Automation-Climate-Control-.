# 🌱 Smart Greenhouse IoT System
----------------------
## 📖 Overview
This project creates a **fully automated greenhouse** using IoT sensors & actuators.  
It monitors **temperature, humidity, CO₂ levels, and light intensity**, and automatically controls **fans, heaters, and grow lights**.

----------------------------------

## ⚙️ Features
- DHT22 sensor for **temperature & humidity**  
- CO₂ sensor for **air quality monitoring**  
- LDR for **light intensity**  
- **Fan, Heater, Grow Light** control with relays  
- MQTT communication between ESP32 and Raspberry Pi  
- CSV data logging on Raspberry Pi  
- Real-time alerts for unsafe conditions  

-------------------
----------------------------------
## 🛠 Hardware
- **ESP32** (MicroPython)  
- **DHT22** (Temp & Humidity)  
- **CO₂ Sensor** (e.g., MQ135 or NDIR sensor)  
- **LDR** (light sensor)  
- **Relay module** + Fan, Heater, LED Grow Light  
- **Raspberry Pi**  

---

## 🧑‍💻 Software
- MicroPython on ESP32  
- Python 3 on Raspberry Pi  
- Dependencies:
```bash
pip install paho-mqtt
