# 🚨 SafeCampus – Disaster Preparedness & Emergency Response System

## 📌 Overview

**SafeCampus** is a web-based disaster preparedness and emergency response platform designed for educational campuses. The system helps students and staff prepare for disasters, learn safety procedures, and respond quickly during emergencies.

The platform provides real-time safety guidance, evacuation support, preparedness assessments, and interactive training modules to improve campus safety awareness.

---

## 🎯 Problem Statement

Educational campuses often lack accessible and interactive tools that help students prepare for disasters such as fires, earthquakes, floods, and cyclones. During emergencies, people panic and do not know the correct safety procedures.

**SafeCampus solves this problem by providing a centralized disaster preparedness system that offers guidance, training, and emergency support.**

---

## ✨ Key Features

### 🚨 Emergency Panic Mode

* One-click emergency activation
* Displays instant safety instructions
* Shows emergency contacts
* Alerts users with visual notifications

### 📊 Preparedness Score System

* Safety checklist evaluation
* Calculates preparedness percentage
* Shows readiness level (Prepared / Needs Improvement / At Risk)

### 🧭 Smart Evacuation Route Finder

* Simulates campus evacuation routes
* Uses BFS pathfinding algorithm
* Suggests the shortest and safest path to exits

### 🤖 AI Disaster Safety Assistant

* Chat assistant for disaster-related questions
* Provides safety instructions instantly

### 🔊 Voice Safety Instructions

* Reads emergency instructions aloud using browser speech synthesis

### 🗺 Campus Emergency Map

Displays important campus safety locations:

* Fire exits
* Assembly points
* Medical room
* Fire extinguishers

### 📢 Emergency Alert Broadcast

* Simulates campus-wide emergency alerts
* Notifies users of ongoing incidents

### 🎮 Disaster Training Simulation

Interactive learning module where users answer safety questions during simulated disasters.

### 📈 Safety Dashboard

Visual dashboard displaying preparedness levels for different disasters.

### 🎒 Emergency Kit Checklist

Guidelines for essential disaster preparedness supplies.

### 📍 Location-Based Emergency Services

Uses geolocation to show nearby hospitals, police stations, and fire departments.

### 🏆 Preparedness Certificate

Users who complete training modules receive a digital safety certificate.

---

## 🛠 Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript (ES6)

### Libraries & APIs

* Bootstrap
* FontAwesome
* Chart.js
* Leaflet.js
* EmailJS
* Web Speech API
* Geolocation API
* LocalStorage API

---

## 📁 Project Structure

```
SafeCampus/
│
├── index.html
├── dashboard.html
├── simulation.html
├── map.html
│
├── css/
├── js/
├── assets/
├── data/
├── utils/
│
├── requirements.txt
└── README.md
```

---

## ⚙️ How to Run the Project

1. Clone the repository

```
git clone https://github.com/yourusername/SafeCampus.git
```

2. Navigate to the project folder

```
cd SafeCampus
```

3. Open the project

```
open index.html
```

or run using a local server such as VS Code Live Server.

---

## 🧠 Algorithms Used

### Breadth First Search (BFS)

Used to determine the shortest evacuation route to the nearest exit.

### Preparedness Score Calculation

```
Preparedness Score = (Completed Safety Tasks / Total Tasks) × 100
```

---

## 🌍 Future Improvements

* Real-time disaster alerts
* Integration with campus security systems
* Mobile application version
* IoT sensors for fire and earthquake detection
* Push notifications for emergencies

---

## 👥 Team

Developed for Hackathon Project – SafeCampus Disaster Preparedness System.

---

## 📜 License

This project is developed for educational and hackathon purposes.
