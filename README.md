# 🚑 Smart Ambulance Traffic Management System

A smart, simulation-based system designed to **reduce ambulance response time** by automatically managing traffic signals using **geofencing and priority-based signal preemption**.

This project demonstrates how intelligent systems and real-time decision logic can be applied to **emergency traffic management** in smart cities.

---

## 📌 Problem Statement

In urban areas, ambulances often get delayed due to traffic congestion and lack of coordinated signal control. Traditional traffic systems do not prioritize emergency vehicles, leading to critical delays and loss of life.

---

## 💡 Proposed Solution

The **Smart Ambulance Traffic Management System** detects ambulances as they approach traffic junctions and **automatically switches traffic signals to GREEN**, ensuring a clear and uninterrupted path. Once the ambulance passes, signals return to normal operation.

---

## 🎯 Objectives

- Minimize ambulance travel time
- Automate traffic signal control for emergency vehicles
- Avoid manual intervention by traffic police
- Enable real-time monitoring and event logging
- Simulate real-world emergency scenarios effectively

---

## 🧠 System Features

- 🚦 **Automatic Traffic Signal Preemption**
- 📍 **Geofence-based Ambulance Detection (200m radius)**
- 🚑 **Multiple Ambulance Handling**
- 🧭 **Live Navigation & Route Selection**
- 🧾 **Real-time Event Logging**
- 🔁 **Automatic Signal Recovery**
- 🔐 **Driver Login & Dashboard**

---

## 🏗️ System Architecture

**Workflow Overview:**
1. Ambulance starts journey
2. Enters junction geofence
3. System detects ambulance
4. Traffic signal switches to GREEN
5. Ambulance passes junction
6. Signal resets to normal

---

## 👥 User Roles

### 🚑 Ambulance Driver
- Login to system
- Select pickup & drop location
- Set emergency severity
- View live navigation

### 🛠️ System (Automated)
- Detect ambulance entry into geofence
- Control traffic signals
- Log events and system actions

---

## ⚙️ Technologies Used

### Software
- **Programming Language:** Python  
- **Framework (Simulation/UI):** Web-based dashboard  
- **Database:** SQLite / MySQL  
- **IDE:** VS Code  

### Hardware (For Real Deployment)
- GPS module
- IoT-enabled traffic signals
- Server or edge device (Raspberry Pi)

---

## 🧪 Simulation Details

- Multiple junctions simulated (Silk Board, BTM, HSR, etc.)
- Ambulances move on predefined routes
- Each junction has a virtual geofence
- Signal override happens instantly on detection
- Event log records all activities with timestamps

---

## 📊 Results & Observations

- ✅ Accurate geofence detection
- ⚡ Instant signal switching
- 🚑 Multiple ambulances handled simultaneously
- 🔄 Smooth recovery after ambulance passes
- 🧾 Real-time logs improve transparency

---

## 📸 Screens (Included in Report)

- Driver Login Page  
- Driver Dashboard  
- Emergency Severity Selection  
- Live Ambulance Navigation  
- Traffic Signal Simulation View  

---

## 🔒 Security Considerations

- Role-based access (Driver / System)
- Secure handling of login credentials
- Controlled signal override logic
- Event logging for auditing

---

## 🚀 Future Enhancements

- Real-world IoT deployment
- GPS-based real-time tracking
- Integration with city traffic systems
- Mobile app for drivers
- AI-based traffic density prediction

---

## 📚 References

- OpenCV Documentation  
- Face Recognition Library (Python – Dlib)  
- SQLite Official Documentation  
- ISO/IEC Biometric Standards  

---

## 👨‍💻 Developed By

**Department of Computer Science & Engineering**  
T. John Institute of Technology  
Academic Year: **2025–2026**

---

⭐ If you like this project, give it a star and feel free to fork it!
