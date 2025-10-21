# 📡 Antenna Azimuth and Rotation Control System

## 🧭 Project Overview
This project aims to develop a **closed-loop antenna positioning system** capable of **automatic azimuth (horizontal)** and **elevation (vertical)** control.  
The system ensures accurate antenna alignment for cellular or communication towers using **STM32 microcontroller-based control**, **motor drivers**, and **position feedback sensors**.

The final design will be **production-grade**, including:
- Optimized firmware (PID closed-loop control)
- Hardware protection (limit switches, current limits)
- Remote monitoring & telemetry interface
- Production-ready PCB design and documentation

---

## ⚙️ System Architecture
### Main Functional Blocks
| Block | Description |
|--------|-------------|
| **STM32 MCU** | Core controller for processing feedback and generating control signals |
| **Motor Drivers** | Control azimuth and elevation motors (DC/Stepper) |
| **Position Sensors** | Rotary encoders or potentiometers for angular feedback |
| **Limit Switches** | Safety stops for mechanical limits |
| **Power Supply** | 12–24V DC source for motor and logic circuits |
| **Telemetry Unit** | Wi-Fi / Ethernet / RS485 communication to remote dashboard |
| **Control GUI** | PC or web-based monitoring and manual control interface |

---

## 🎯 Objectives
1. Maintain antenna azimuth and elevation automatically with ±0.5° precision.  
2. Implement a **closed-loop control algorithm (PID)** for smooth and stable positioning.  
3. Support **remote angle commands and live telemetry** (position, status, faults).  
4. Provide **fail-safe operation** using limit switches and emergency stop routines.  
5. Deliver a **production-ready PCB**, firmware, and documentation.

---

## 🧩 Hardware Components (Initial Plan)
| Component | Example / Part No. | Function |
|------------|-------------------|-----------|
| Microcontroller | STM32F407 / STM32F103 | Main control unit |
| DC/Stepper Motor | NEMA17 / 12V Geared DC | Antenna rotation |
| Motor Driver | L298N / BTS7960 / TB6600 | Motor actuation |
| Feedback Sensor | Rotary Encoder / 10k Potentiometer | Position feedback |
| Limit Switch | Mechanical / Optical | Movement boundaries |
| Power Supply | 12–24V DC | System power |
| Communication Module | ESP8266 / RS485 / Ethernet | Remote control interface |

---

## 🧰 Development Tools
| Tool | Purpose |
|------|----------|
| **STM32CubeIDE** | Firmware development (HAL/LL drivers) |
| **STM32CubeMX** | Peripheral and pinout configuration |
| **ST-Link V2** | Programming and debugging interface |
| **Proteus (Optional)** | Simulation and system testing |
| **GitHub** | Version control and documentation management |

---

## 🧪 Project Phases
| Phase | Description |
|-------|-------------|
| **Day 1–3:** | System definition, environment setup, hardware block diagram |
| **Day 4–7:** | Sensor interfacing and motor control (open loop) |
| **Day 8–12:** | Closed-loop control development (PID implementation) |
| **Day 13–17:** | Telemetry & communication interface |
| **Day 18–22:** | PCB schematic and layout design |
| **Day 23–25:** | Testing, safety validation, and documentation |

---

## 🧾 Day 1 Progress
- ✅ Defined project scope and goals  
- ✅ Installed STM32CubeIDE and created workspace  
- ✅ Created preliminary system block diagram  
- ✅ Identified key components and drivers  
- ✅ Initialized GitHub repository and README

---

## 🗂 Repository Structure (Planned)
