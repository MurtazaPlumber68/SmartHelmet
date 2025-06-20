# 🛡️ IoT-Based Smart Helmet and Clothing System for Mining Safety

This project leverages **Internet of Things (IoT)** to enhance miner safety through a **smart helmet and clothing system** capable of real-time environmental and health monitoring. It detects hazardous gases, monitors body status, helmet integrity, water levels, and transmits data to a central control system as well as a Firebase database for live updates and alerts.

---

## 📌 Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [System Architecture](#system-architecture)
- [Technologies Used](#technologies-used)
- [Hardware Components](#hardware-components)
- [Software Requirements](#software-requirements)
- [Setup Instructions](#setup-instructions)
- [Folder Structure](#folder-structure)
- [Results](#results)
- [Future Enhancements](#future-enhancements)
- [Contributors](#contributors)

---

## 📖 Introduction

Mining environments are inherently dangerous due to risks like toxic gases, flooding, poor ventilation, and equipment damage. This smart helmet and clothing system provides real-time alerts and monitoring of:

- Temperature & humidity levels
- Presence of gases like methane
- Miner consciousness & helmet status
- Flood water levels
- Physical damage to the helmet

The data is sent wirelessly to a **control room dashboard** and also synced with **Google Firebase** for monitoring via mobile applications.

---

## 🚀 Features

- ⚠️ Real-time hazard detection & alerting  
- ⛑️ Helmet removal and obstacle impact detection  
- 🌡️ Environmental monitoring (temperature, humidity, gases)  
- 🔋 Piezoelectric-based battery charging  
- 🌊 Flood detection using water sensors  
- 📶 Wireless communication (Wi-Fi/Bluetooth)  
- ☁️ Google Firebase integration  
- 📲 Mobile notification support  
- 🧠 Miner conscious/unconscious state monitoring  

---

## 🧱 System Architecture

- **Helmet Section:** Sensor data collection, processing via microcontroller, wireless data transmission  
- **Control Room Section:** Data reception, dashboard display, Firebase sync  
- **Cloud Sync:** Firebase for real-time data updates and mobile app access  

---

## 🛠️ Technologies Used

- ⚙️ **Arduino IDE**, C/C++  
- ☁️ **Google Firebase (Realtime Database)**  
- 📡 **MQTT protocol**  
- 📱 **Android Studio (for mobile app)**  
- 📐 PCB Design Tools  
- 💬 Serial Monitor for debugging  

---

## 🔌 Hardware Components

- NodeMCU (ESP8266/ESP32)  
- Arduino UNO/Nano  
- IR Sensors  
- Gas Sensor (MQ series)  
- Humidity & Temperature Sensor (DHT11/DHT22)  
- Proximity Sensor  
- Water Level Sensor  
- Piezoelectric Sensor (for impact)  
- Buzzer, LEDs  
- Rechargeable Battery Module  

---

## 💻 Software Requirements

- Arduino IDE  
- Firebase Console  
- Android Studio (optional for mobile app)  
- MQTT Client Dashboard (for testing)  
- USB Driver for Arduino/NodeMCU  

---

## 🧪 Setup Instructions

1. **Hardware Assembly**
   - Connect sensors to NodeMCU and Arduino as per the [PCB Design](#).
   - Power up with a battery or USB.

2. **Upload Code**
   - Use Arduino IDE to upload `Helmet Code` and `Watch Code` from `source_code/`.

3. **Firebase Setup**
   - Create a Firebase project.
   - Enable Realtime Database.
   - Update database URL and credentials in the Arduino code.

4. **Mobile App (Optional)**
   - Import the Android project in Android Studio.
   - Link with the same Firebase project.

5. **Testing**
   - Use the Serial Monitor to verify sensor readings.
   - Simulate gas/heat/impact to test responses.

---


## 📊 Results

- 🚧 Successful detection of key hazardous events during testing  
- 📲 Real-time alerts synced to Firebase  
- 📈 Increased situational awareness for mining supervisors and family members  
- ⚡ Sensor-based triggers improved miner safety response times  

---

## 🔮 Future Enhancements

- Integrate GPS for location tracking  
- Add voice-activated SOS signal  
- Improve battery life using solar panels  
- Expand to include fatigue and posture analysis via wearables  
- Integration with AI-based predictive maintenance models  

---


> This project is developed as part of the final year engineering curriculum. Contributions and suggestions are welcome!
