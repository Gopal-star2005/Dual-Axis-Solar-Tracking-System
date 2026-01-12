# ☀️ Arduino-Based Dual Axis Solar Tracking System

![Status](https://img.shields.io/badge/status-completed-success)
![Platform](https://img.shields.io/badge/platform-Arduino-blue)
![Domain](https://img.shields.io/badge/domain-Renewable%20Energy-green)
![License](https://img.shields.io/badge/license-MIT%20(Code)%20%7C%20All%20Rights%20Reserved%20(Assets)-red)

⚡ An embedded systems project that dynamically aligns a solar panel along **both horizontal and vertical axes** to maximize solar energy absorption throughout the day.

This repository demonstrates **practical implementation of renewable energy concepts**, real-time sensor feedback, and actuator control using Arduino.

---

## 📌 Project Overview

The **Dual Axis Solar Tracking System** automatically adjusts the orientation of a solar panel based on sunlight intensity detected using **Light Dependent Resistors (LDRs)**.  
Unlike fixed or single-axis systems, this solution tracks the sun in **two dimensions**, significantly improving energy efficiency.

The project is designed with **simplicity, modularity, and academic clarity**, making it suitable for:
- Engineering mini/major projects
- Renewable energy demonstrations
- Embedded systems learning
- IoT and automation foundations

---

## 🧠 Working Principle

- Four LDR sensors are placed around the solar panel to detect sunlight from different directions.
- The Arduino continuously compares LDR readings.
- Two servo motors rotate the panel:
  - **Horizontal axis (Azimuth)**
  - **Vertical axis (Elevation)**
- The panel aligns itself toward the direction with maximum light intensity.
- This process runs continuously for real-time sun tracking.

---

## ✨ Key Features

- 🔄 Dual-axis (azimuth + elevation) tracking
- 🌞 Real-time sunlight intensity comparison
- ⚙️ Servo motor–based precise control
- 🔋 Improved power output vs fixed panels
- 🧩 Modular and extensible Arduino code
- 📚 Beginner-friendly yet conceptually strong

---

## 🧰 Hardware Components

- Arduino Uno / Arduino Nano  
- 4 × LDR Sensors  
- 2 × Servo Motors  
- Resistors  
- Solar Panel  
- Mounting Frame  
- External Power Supply  
- Connecting Wires  

---

## 🛠 Software & Tools

- **Arduino IDE**
- **Embedded C / C++**
- Servo Motor Library  
- (Optional) LCD Display Library  

---


