# ⌚ FitTrack Pro – Smart Fitness Dashboard

A real-time fitness tracking web application that simulates data from wearable sensors like MPU6050, MAX30102, and GPS.  
This project demonstrates how IoT-based health monitoring systems can be visualized using a modern web dashboard.

---

## 🚀 Features

- ❤️ Live Heart Rate Monitoring (Simulated)
- 🫁 SpO₂ Tracking
- 👣 Step Counter
- 🤖 Activity Detection (Walking / Running / Workout)
- 🔥 Calories Burned Calculation
- 📏 Distance & ⚡ Speed Tracking
- 📈 Real-time Heart Rate Graph (Rolling Window)
- 📍 Live GPS Movement Simulation with Map
- 📄 Downloadable Fitness Report (PDF)
- 📱 Fully Responsive (Mobile + Desktop)

---

## 🧠 AI-Based Logic (Simulated)

- If heart rate > 120 → **Workout Mode 🔥**
- If steps increase rapidly → **Running 🏃**
- Otherwise → **Walking 🚶**

---

## 🛠️ Technologies Used

- HTML5  
- CSS3 (Responsive UI)  
- JavaScript  
- Chart.js (Graph Visualization)  
- Leaflet.js (Map Integration)  
- jsPDF (Report Generation)

---

## 📊 System Architecture

Sensors → Data Processing → Web Dashboard → Visualization → Report Generation

---

## 📱 How to Run Locally

1. Download or clone this repository  
2. Open `index.html` in your browser  

OR

Run a local server:
```bash
python -m http.server 8000
