# 🌱 AgroSense – Smart Agriculture IoT System

> End-to-end IoT system for real-time agricultural monitoring, automation, and 3D visualization (Digital Twin)

---

## 🚀 Overview

AgroSense is a full-stack IoT solution designed to monitor environmental conditions in agricultural environments and enable intelligent, data-driven decisions.

The system integrates:

- Embedded systems (ESP32 + sensors)
- Backend API (data ingestion & processing)
- Real-time web dashboard
- 3D Digital Twin visualization (Unity)
- Smart automation (irrigation control)

---

## 🧠 Key Features

- Real-time environmental monitoring  
- Temperature & humidity tracking  
- Soil moisture analysis  
- Historical data visualization  
- Smart alerts (low moisture detection)  
- Automated irrigation system  
- 3D Digital Twin simulation  

---

## 🏗️ System Architecture

Sensors → ESP32 → API (HTTP/MQTT) → Database → Dashboard → Unity

---

## 🔧 Tech Stack

Embedded: ESP32 (C++ / Arduino)  
Communication: HTTP / MQTT  
Backend: FastAPI (Python)  
Database: PostgreSQL / SQLite  
Frontend: React  
Visualization: Unity (C#)  

---

## 🔌 Hardware Components

- ESP32 microcontroller  
- Soil moisture sensor  
- DHT11 (temperature & humidity)  
- OLED display (I2C)  
- Relay module (for irrigation automation)  

---

## 📦 Data Model

Example payload:
```
{
  "soil_moisture": 62,
  "temperature": 28,
  "humidity": 70,
  "timestamp": "2026-04-05T14:00:00"
}
```
---

## ⚙️ Backend API
```
POST /sensor-data
```
Responsibilities:

- Receive sensor data  
- Store historical records  
- Trigger alerts  
- Serve data to dashboard & Unity  

---

## 📊 Dashboard

- Real-time visualization  
- Historical charts  
- Soil condition indicators  
- Alert system  

---

## 🎮 Digital Twin (Unity)

- Healthy plants (optimal conditions)  
- Dry plants (low soil moisture)  
- Dynamic environmental updates  

---

## 🤖 Automation Logic
```
IF soil_moisture < threshold:
    activate_irrigation()
```
---

## 🧪 Future Improvements

- Machine learning for predictive irrigation  
- Weather API integration  
- Mobile app (Flutter / React Native)  
- Multi-device support  
- Edge computing optimizations  

---

## 🛠️ Setup Instructions

Backend:
```
git clone https://github.com/your-username/agrosense
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```
Frontend:
```
cd frontend
npm install
npm start
```
ESP32:

- Configure Wi-Fi credentials  
- Set API endpoint  
- Upload firmware via Arduino IDE  

---

## 📈 Project Goals

- Real-world IoT system design  
- Distributed architecture  
- Hardware-software integration  
- Scalable backend development  
- Digital Twin visualization  

---

## 💼 Why This Project Matters

- End-to-end engineering capability  
- Real-time data pipelines  
- Embedded + backend + frontend integration  
- Practical AgTech application  

---

## 📷 Demo

Coming soon...

---

## 📄 License

MIT License

---

## 👨‍💻 Author

Emanuel Ferreira
