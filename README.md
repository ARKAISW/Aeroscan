# ✈️ AeroScan: Smart Airport Radar System

> Detect • Track • Protect

AeroScan is an Arduino-based radar system that simulates how real-world airport radar detects and tracks objects, especially in low-visibility conditions like fog or heavy rain.

---

## 🚀 Overview

Modern airports rely on radar systems to ensure safe aircraft movement when human visibility is limited. AeroScan recreates this concept on a smaller scale using ultrasonic sensing and real-time visualization.

This project demonstrates how machines can:
- Detect objects
- Measure distance
- Map surroundings dynamically

---

## 🎯 Problem Statement

In low-visibility conditions:
- Pilots cannot rely on eyesight
- Ground vehicles may enter runways unnoticed
- Risk of collision increases significantly

A reliable detection system is required to:
- Monitor surroundings
- Track object positions
- Prevent accidents

---

## 💡 Solution

AeroScan provides a simplified radar system that:
- Continuously scans a 180° area
- Detects nearby objects
- Displays their position in real-time

---

## ⚙️ How It Works

1. A servo motor rotates the ultrasonic sensor from **15° to 165°**
2. The sensor emits ultrasonic waves
3. Waves reflect off nearby objects
4. Time-of-flight is measured to calculate distance
5. Arduino sends **angle + distance** data via serial communication
6. Processing converts this data into a **live radar display**

---

## 🧠 Core Concept

Unlike real radar systems that use **radio waves**, AeroScan uses **ultrasonic sound waves**.

However, the fundamental principle remains the same:
> Detect objects by measuring reflected waves.

---

## 🖥️ Features

- 📡 180° radar scanning  
- 📏 Real-time distance measurement  
- 🟢 Live radar visualization  
- 🔄 Continuous scanning system  
- 💰 Low-cost implementation  

---

## 🧰 Tech Stack

- **Arduino (C++)**
- **Ultrasonic Sensor (HC-SR04)**
- **Servo Motor**
- **Processing (Java-based visualization)**

---


---

## 📸 Demo

![AeroScan Model](./assets/demo.jpg)

---

## 🌍 Real-Life Applications

- ✈️ Airport runway monitoring  
- 🚗 Self-driving vehicle obstacle detection  
- 🚢 Maritime SONAR systems  
- 🛰️ Defense and surveillance systems  

---

## 📖 Use Case Scenario

Imagine an airport during dense fog.

An aircraft is taxiing on the runway while a ground vehicle mistakenly enters the same path.

Without radar, this could lead to a collision.

AeroScan detects both objects, displays their position, and allows timely intervention — preventing accidents.

---

## ⚠️ Limitations

- Limited range (~40 cm)
- Uses ultrasonic waves instead of radio waves
- Lower accuracy compared to industrial systems
- Cannot identify object type (only detects presence)

---

## 🔮 Future Improvements

- 360° scanning system  
- Long-range sensors (LiDAR / RF modules)  
- AI-based object classification  
- IoT integration for remote monitoring  

---

## 👨‍💻 Author

**Arka Sarkar**  
Birla High School, Mukundapur  

---

## ⭐ Support

If you found this project interesting, consider giving it a star ⭐
