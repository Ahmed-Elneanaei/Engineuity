# Engineuity 
Smart Vehicle Diagnostics & Predictive Maintenance using Machine Learning

Engineuity is a cross-platform mobile application designed to make vehicle maintenance smarter, safer, and proactive. Instead of reacting to breakdowns, Engineuity predicts potential faults before they occur using real-time OBD-II sensor data and a Bidirectional Long Short-Term Memory (Bi-LSTM) deep learning model.

The app connects to a vehicle’s OBD-II port via Bluetooth, streams live parameters such as RPM, coolant temperature, voltage, and other telemetry, then analyzes these time-series signals to provide:

• Real-time diagnostics  
• Current fault detection  
• Future failure prediction  
• Maintenance reminders  
• Historical vehicle health tracking  

Built with **Flutter** for a clean and intuitive user experience, Engineuity is tailored for non-technical drivers, offering simple navigation, clear alerts, and visual indicators.

The backend architecture combines:

- **Firebase** – authentication, cloud storage, and data sync  
- **Flask API** – prediction service  
- **PyTorch** – Bi-LSTM fault prediction model  
- **OBD-II Bluetooth interface** – live vehicle telemetry  

Engineuity supports both **ICE and EV vehicles** and demonstrates how machine learning can enhance road safety and reduce unexpected maintenance costs.

---

## Tech Stack

Frontend: Flutter  
Backend: Flask (Python)  
ML: PyTorch (Bi-LSTM)  
Database/Auth: Firebase  
Hardware Interface: OBD-II Bluetooth  

---

## Project Type

Final Year Computer Science Graduation Project  
Focus areas: Mobile Development • Machine Learning • IoT/Vehicle Telemetry • Predictive Analytics
