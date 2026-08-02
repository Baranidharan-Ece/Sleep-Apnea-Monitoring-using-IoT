# 💤 Sleep Apnea Monitoring using IoT

![ESP32](https://img.shields.io/badge/ESP32-WiFi-blue)
![IoT](https://img.shields.io/badge/IoT-Healthcare-green)
![MAX30100](https://img.shields.io/badge/MAX30100-SpO2-red)
![Arduino](https://img.shields.io/badge/Embedded-C++-orange)
![License](https://img.shields.io/badge/License-MIT-yellow)

## 📖 Overview

Sleep Apnea is a serious sleep disorder where breathing repeatedly stops and starts during sleep. This project presents an IoT-enabled healthcare monitoring system that continuously measures vital physiological parameters such as blood oxygen saturation (SpO₂), heart rate, respiration, temperature, humidity, and body movement.

The collected data is processed by the ESP32 microcontroller and transmitted wirelessly for remote patient monitoring, enabling early detection of abnormal breathing events.

---

## ✨ Features

- 🫀 Real-Time Heart Rate Monitoring
- 🩸 Blood Oxygen (SpO₂) Monitoring
- 🌡 Temperature & Humidity Monitoring
- 😴 Respiration Monitoring
- 📈 Body Movement Detection
- ☁ IoT Cloud Monitoring
- 📱 Remote Healthcare Dashboard
- ⚡ Low Power Embedded Design

---

# 🛠 Hardware Components

- ESP32 Development Board
- MAX30100 Pulse Oximeter
- DHT11 Sensor
- Respiration (Sound) Sensor
- Accelerometer Sensor
- Compressor
- Power Supply

---

# 💻 Software

- Arduino IDE
- Embedded C++
- ESP32 Libraries
- IoT Cloud Platform

---

# 🧩 System Architecture

<p align="center">
<img src="images/BlockDiagram.png" width="900">
</p>

---

# 🔌 Circuit Diagram

<p align="center">
<img src="images/CircuitDiagram.png" width="900">
</p>

---

# ⚙ Working Principle

1. ESP32 initializes all sensors.
2. MAX30100 continuously measures Heart Rate & SpO₂.
3. Respiration sensor detects breathing patterns.
4. DHT11 measures surrounding temperature and humidity.
5. Accelerometer detects body movement during sleep.
6. ESP32 processes all sensor readings.
7. Data is transmitted wirelessly to the IoT dashboard.
8. Abnormal conditions trigger alerts for caregivers.

---

# 📊 Parameters Monitored

| Parameter | Sensor |
|-----------|--------|
| Heart Rate | MAX30100 |
| Blood Oxygen (SpO₂) | MAX30100 |
| Respiration | Sound Sensor |
| Temperature | DHT11 |
| Humidity | DHT11 |
| Body Movement | Accelerometer |

---

# 🚀 Future Scope

- AI-based Sleep Apnea Prediction
- TinyML Edge Inference
- Mobile Application
- MQTT Cloud Integration
- Doctor Dashboard
- Automatic Emergency Alert
- Wearable Healthcare Device

---

# 📄 Documentation

- 📘 Working Principle
- 📑 Complete Project Report
- 📊 Circuit Diagram
- 📈 Block Diagram

---

# 👨‍💻 Author

**Baranidharan S**

Electronics & Communication Engineering

IoT | Embedded Systems | Healthcare Technology
