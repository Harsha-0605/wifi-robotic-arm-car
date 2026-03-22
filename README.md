# WiFi Controlled Robotic Arm Car

![Robot](images/robot_arm.jpg)

## Overview
The WiFi Controlled Robotic Arm Car is an IoT-based robotic system that allows remote control of a vehicle along with a robotic arm for object manipulation.

This project demonstrates real-time wireless control, robotics, and embedded systems integration.

---

## Features
- WiFi-based remote control using ESP32
- Robotic arm for pick and place operations
- Real-time movement control
- Wireless communication
- Multi-motor control system
- Dual motor driver control system (separate control for car and arm)

---

## Problem Statement
Manual handling of objects in hazardous or inaccessible environments can be risky.  
This system enables remote control of a robotic arm to perform tasks safely.

---

## Hardware Components
| Component | Description |
|----------|-------------|
| ESP32 | Microcontroller with WiFi |
| L298N Motor Driver (x2) | Controls DC motors |
| DC Motors (x4) | 2 for car movement, 2 for robotic arm |
| Robotic Arm Mechanism | Object handling |
| Chassis | Base structure |
| Battery | Power supply |

---

## Software & Technologies
- Embedded C / Arduino IDE
- ESP32 WiFi communication
- Mobile/Web control interface

---

## Working Principle
1. User sends commands via WiFi (mobile/web app).
2. ESP32 receives commands.
3. Motor driver controls car movement.
4. Servo motors control robotic arm.
5. Robot performs pick-and-place operations.

---

## Circuit Diagram
Refer to the **circuit** folder for complete connections.

---

## Applications
- Industrial automation
- Remote object handling
- Hazardous environment operations
- Robotics learning projects

---

## Future Improvements
- Camera integration for live video
- AI-based object detection
- Voice control
- Autonomous navigation

---

## Author
Harsha Teja  
Embedded Systems | IoT | AIoT Enthusiast
