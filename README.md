# 🔑 Smart Door System using IoT

This project is an **IoT-based Keyless Entry System** that allows users to lock and unlock a door remotely using **Adafruit IO (MQTT) or Blynk Cloud**. The system enhances security by eliminating the need for physical keys and provides real-time access control.

## 📌 Features
- 🚪 **Remote Door Lock/Unlock** using IoT.
- 🔔 **Buzzer Alert** for unauthorized access.
- 📡 **Adafruit IO (MQTT) or Blynk Cloud** integration.
- ⚡ **Real-time control** via smartphone or web dashboard.
- 🔄 **Auto Reconnect** to WiFi in case of disconnection.

## 🔧 Components Required
- 🟦 **ESP8266 NodeMCU**
- 🔄 **Relay Module**
- 🔊 **Buzzer**
- 🔌 **Power Supply**
- 📡 **WiFi Connection**
- 🏠 **Adafruit IO / Blynk Cloud Account**

## 🔌 Circuit Diagram
![Wi-Fi-Door-Lock-Circuit-Diagram](https://github.com/user-attachments/assets/d408bef3-5c19-46f0-b310-9c139c1b6e02)


## 🛠️ Setup Instructions
### **1️⃣ Hardware Connections**
- Connect **ESP8266** to the **relay module** and **buzzer** as per the circuit diagram.
- Ensure proper **power supply** to the components.

### **2️⃣ Software Setup**
#### **For Adafruit IO (MQTT)**
1. Sign up on [Adafruit IO](https://io.adafruit.com/).
2. Create a new **feed** (e.g., `Lock`).
3. Copy your **Adafruit IO Username & API Key**.
4. Replace these credentials in the `WiFi` and `MQTT` sections of the code.

#### **For Blynk Cloud**
1. Sign up on [Blynk](https://blynk.io/).
2. Create a new project & get the **Auth Token**.
3. Replace **Auth Token, WiFi SSID, and Password** in the Blynk code.

### **3️⃣ Upload Code**
- Install **Arduino IDE** with ESP8266 board support.
- Install required libraries: 
  - `Adafruit MQTT Library`
  - `Blynk Library`
- Upload the respective code based on your IoT platform.

## 📲 Usage
- 🏠 **Adafruit IO:** Send `Open` or `Close` commands from the dashboard.
- 📱 **Blynk App:** Tap buttons to control relays for door access.
- 🔔 Buzzer alerts on unauthorized access attempts.



🔗 **Contribute & Star ⭐ this repository if you find it useful!**
