# ESP32 MQTT Chat

This project demonstrates **two-way communication** between an ESP32 and an MQTT broker.  
You can use it to send and receive messages over WiFi, making it useful for IoT chat systems, debugging, or lightweight device communication.

---

## 🚀 Features
- Connects ESP32 to WiFi.
- Connects ESP32 to a public MQTT broker (`broker.mqtt-dashboard.com`).
- Subscribes to a topic (`esp32/chat`) and prints incoming messages.
- Publishes messages entered via the **Serial Monitor** to the same topic.
- Automatically reconnects if WiFi/MQTT connection is lost.

---

## 🛠️ Hardware Requirements
- ESP32 Development Board
- Micro-USB cable
- WiFi network with internet access

---

## 📦 Software Requirements
- [Arduino IDE](https://www.arduino.cc/en/software) (or PlatformIO in VS Code)
- Install the following libraries:
  - `WiFi.h` (built-in for ESP32 boards)
  - `PubSubClient` (by Nick O’Leary)

---

## ⚙️ Setup Instructions
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/esp32-mqtt-chat.git
   cd esp32-mqtt-chat

