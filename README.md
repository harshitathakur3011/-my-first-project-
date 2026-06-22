# -my-first-project-
"Arduino-powered smart home automation system for controlling lights and fans remotely via an Android mobile app."
Smart Home Automation System using Arduino Uno, PICSimLab, and Blynk IoT

📖 Project Overview

The Smart Home Automation System is an IoT-based project developed using Arduino Uno and simulated in PICSimLab. The system integrates with the Blynk IoT platform to enable remote monitoring and control of home appliances and environmental parameters through a smartphone application.

The project allows users to control a cooler, heater, inlet valve, and outlet valve while monitoring temperature and water volume levels in real time.

---

🎯 Objectives

- Automate home appliance control using IoT technology.
- Monitor environmental conditions remotely.
- Simulate embedded systems using PICSimLab.
- Integrate Arduino Uno with the Blynk IoT platform.
- Develop a user-friendly mobile control interface.

---

🛠 Technologies Used

- Arduino Uno
- Arduino IDE
- PICSimLab
- Blynk IoT Platform
- Embedded C/C++
- Serial Communication

---

🔧 Components Used

Component| Description
Arduino Uno| Main Controller
PICSimLab| Simulation Environment
Blynk IoT App| Mobile Dashboard
Cooler| Cooling Device
Heater| Heating Device
Inlet Valve| Water Input Control
Outlet Valve| Water Output Control
Temperature Sensor| Temperature Monitoring
Volume Sensor| Water Level Monitoring

---

📱 Blynk Virtual Pin Configuration

Function| Virtual Pin
Cooler Control| V0
Temperature Monitoring| V1
Heater Control| V2
Volume Monitoring| V3
Inlet Valve Control| V4
Outlet Valve Control| V5

---

⚙️ System Working

1. The Arduino Uno continuously monitors temperature and volume sensor values.
2. Sensor data is transmitted to the Blynk Cloud platform.
3. The Blynk mobile application displays real-time values for:
   - Temperature (V1)
   - Volume (V3)
4. Users can remotely control:
   - Cooler (V0)
   - Heater (V2)
   - Inlet Valve (V4)
   - Outlet Valve (V5)
5. Commands from the Blynk app are sent to Arduino through the cloud connection and executed immediately.

---

🚀 Features

- Real-time temperature monitoring
- Real-time water volume monitoring
- Remote cooler control
- Remote heater control
- Inlet valve automation
- Outlet valve automation
- Mobile-based control interface
- IoT cloud connectivity
- PICSimLab simulation support

---

📂 Project Structure

Smart-Home-Automation/
│
├── Arduino_Code/
│   └── HomeAutomation.ino
│
├── PICSimLab/
│   └── Simulation_Project.pzw
│
├── Images/
│   ├── Dashboard.png
│   └── Circuit.png
│
└── README.md

---

🔄 Workflow

Sensors/Actuators
        │
        ▼
   Arduino Uno
        │
        ▼
   Blynk Cloud
        │
        ▼
  Blynk Mobile App

---

📊 Expected Output

- Temperature value updates continuously on V1.
- Volume level updates continuously on V3.
- Cooler can be switched ON/OFF from V0.
- Heater can be switched ON/OFF from V2.
- Inlet Valve can be controlled from V4.
- Outlet Valve can be controlled from V5.
- All changes are reflected in real time on the Blynk dashboard.
<img width="1280" height="767" alt="output1" src="https://github.com/user-attachments/assets/f0bc074b-d118-455e-93b9-83874287f9f7" />
  
<img width="1280" height="767" alt="output2" src="https://github.com/user-attachments/assets/b140a460-857b-491f-96b9-e75b8e4ce9b6" />

<img width="1280" height="766" alt="output3" src="https://github.com/user-attachments/assets/9055cb3a-1433-43fa-a827-e86de8de59d0" />

<img width="1280" height="780" alt="output4" src="https://github.com/user-attachments/assets/77306f9c-6e86-4f1c-979a-9ee4c5b925a6" />

<img width="722" height="1600" alt="output5" src="https://github.com/user-attachments/assets/93407ac5-a240-4d16-9c41-95fe672559d6" />
<img width="722" height="1600" alt="WhatsApp Image 2026-06-22 at 3 30 07 PM" src="https://github.com/user-attachments/assets/0311bf5b-fe6e-4815-87ca-26e709a22376" />

🎓 Learning Outcomes

- Arduino Programming
- IoT Application Development
- Blynk Cloud Integration
- Sensor Monitoring
- Actuator Control
- PICSimLab Simulation
- Smart Home Automation Concepts

---

🔮 Future Enhancements

- Automatic temperature regulation
- Water level threshold alerts
- Voice control using Google Assistant
- Energy monitoring system
- Data logging and analytics dashboard
- AI-based predictive automation

---

👩‍💻 Author

Harshita Thakur

Embedded Systems | IoT | Arduino | PICSimLab

---

📄 License

This project is developed for educational, research, and learning purposes.
