# Wind Turbine Fault Detection and Condition Monitoring System

This project presents a small-scale simulation of a **Wind Turbine Fault Detection and Condition Monitoring System** using **Arduino Uno**, **NodeMCU**, various **sensors**, **ThingSpeak API**, and **Telegram bot** for remote monitoring and alerting. This system is designed to reduce maintenance time and costs by enabling real-time anomaly detection in wind turbines.

---

## 🔧 Features

- Real-time monitoring of temperature, vibration, and foreign object detection.
- Data collected from sensors and transmitted using NodeMCU to ThingSpeak cloud.
- Alerts and turbine status updates sent to users through a Telegram bot interface.
- LCD display for on-site status viewing.
- Simulated wind turbine using a 3V DC motor with blades.

---

## 🧰 Components Used

- Arduino Uno (ATmega328)
- NodeMCU (ESP8266)
- LM35 Temperature Sensor
- Piezoelectric Vibration Sensor
- Infrared (IR) Sensor (Active)
- 16x2 LCD Display
- Small DC Motor (Wind Turbine Simulation)
- ThingSpeak IoT Platform
- Telegram Messenger with Bot

---

## 📐 System Architecture

Wind Turbine (DC Motor)]
|
[ Sensors: Temp, Vibration, IR ]
|
[Arduino UNO] -----> [LCD Display]
|
[NodeMCU ESP8266]
|
[ThingSpeak API]
|
[Telegram Bot Interface]


---

## 🧠 Algorithms

### Arduino + Sensors Logic
1. Read sensor data (temperature, vibration, object detection).
2. Display data on LCD.
3. Send sensor readings to ThingSpeak via NodeMCU.

### Telegram Bot Logic
1. Telegram bot listens for commands from user.
2. Fetches latest data from ThingSpeak API.
3. Sends turbine status and alerts to user.

---

## 🚀 Getting Started

### Requirements

- Arduino IDE
- NodeMCU ESP8266 board support
- ThingSpeak Account
- Telegram App with Bot Token

### For Contact

dhanam7071@gmail.com
