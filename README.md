# Autonomous Embedded Control System 🚗⚙️

An embedded autonomous buggy system built using **Arduino**, integrating **IR sensors, ultrasonic sensors, DC motors, and wireless communication modules** to enable real-time navigation, obstacle detection, and supervisory control.

This project demonstrates **hardware–software integration**, **embedded control logic**, and **system-level design**, developed as part of an engineering design laboratory and extended into a fully autonomous robotic system.

---

## 🔍 Project Overview

The Autonomous Embedded Control System is designed to:
- Navigate autonomously along a predefined track
- Detect obstacles in real time and respond safely
- Perform line following using IR sensors
- Integrate ultrasonic sensing for obstacle avoidance
- Support wireless supervisory control using ZigBee/XBee
- Execute reliable motor control through state-based decision logic

The system was incrementally developed, tested, debugged, and validated across multiple subsystems to ensure robustness and reliability.

---

## 🛠️ Hardware Components

- **Arduino Uno**
- **IR Sensors** (Line following & gantry detection)
- **Ultrasonic Sensor** (Obstacle detection)
- **DC Motors & Motor Driver**
- **Wireless Module (ZigBee/XBee)**
- **Buggy Chassis**
- Breadboard, jumper wires, resistors

---

## 💻 Software & Tools

- **Embedded C / C++**
- **Arduino IDE**
- **Serial Monitor for debugging**
- **X-CTU** (for wireless communication testing)
- **Tinkercad Simulator** (for initial circuit validation)

---

## ⚙️ System Features

### 🚦 Line Following
- Uses IR sensors to detect track boundaries
- Adjusts motor direction dynamically for accurate navigation

### 🧠 State-Based Control Logic
- Navigation, turning, stopping, and obstacle handling implemented using state machines
- Ensures predictable and safe system behavior

### 🚧 Obstacle Detection & Avoidance
- Ultrasonic sensor measures distance in real time
- Buggy stops or reroutes when obstacles are detected within a threshold distance

### 📡 Supervisory Wireless Control
- Wireless commands trigger autonomous operation
- Gantry detection using pulse-width measurement
- System logs state transitions via serial communication

### 🔎 Debugging & Validation
- Serial logging for sensor readings and state transitions
- Incremental subsystem testing (motors, sensors, communication)
- Fault handling for sensor noise, timing issues, and motor control errors

---

## 🧪 Key Experiments Implemented

- LED control and sequencing
- Serial communication and logging
- DC motor motion (forward, backward, left, right)
- IR-based line follower robot
- Ultrasonic-based obstacle avoidance
- Gantry detection using pulse-width analysis
- ZigBee/XBee wireless control
- **Bronze Challenge**:  
  - Autonomous buggy completes multiple track loops  
  - Stops at gantries  
  - Detects obstacles  
  - Parks safely under supervisory control

