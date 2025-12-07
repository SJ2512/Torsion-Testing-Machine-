# Torsion Testing Machine (Current-Based Torque Estimation)

A compact torsion test rig that estimates torque using motor current (ACS712-30A) and measures twist angle with a rotary encoder. The setup uses a BTS7960 motor driver, Arduino Nano, and a 3S LiPo supply. This build demonstrates the core mechanism and electronics for a small-scale torsion tester.

---

## 🔧 Overview

The system applies twist to a test shaft and measures:

- **Torque (via motor current × Kt constant)**
- **Angle of twist (via rotary encoder counts)**

Due to unavailable couplers/rods during the build, full specimen testing wasn’t done — but the motor used can easily rotate steel/aluminium rods up to **≤6 mm diameter**. Future testing will be done once couplers arrive.

This project focuses on the **working prototype**, electronics, sensing method, and motion system.

---

## 🛠 Hardware Used

- Arduino Nano  
- BTS7960 motor driver  
- ACS712-30A current sensor  
- Rotary encoder (600 CPR assumed)  
- 3S LiPo (11.1 V, 4500 mAh)  
- DC motor  
- Basic mechanical frame + shaft mounts  

---

## 📸 Images

See `/images` folder:

- **main.jpg** — full setup  
- **closeup-sensor.jpg** — current sensor + wiring  
- **encoder.jpg** — encoder mount (if available)

---

## 🎥 Demo

Short demonstration video is also available in the demo folder

