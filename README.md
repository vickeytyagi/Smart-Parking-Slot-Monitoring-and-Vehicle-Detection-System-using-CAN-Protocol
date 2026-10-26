# Smart Parking Slot Monitoring and Vehicle Detection System Using CAN Protocol

## 📌 Project Overview
An ARM7 LPC2129-based Smart Parking System developed using Embedded C and CAN protocol. The system monitors parking slot availability, detects vehicle entry and exit using IR sensors, displays real-time status on a 20×4 LCD, integrates a DS1307 RTC via I2C, and controls the parking gate using a servo motor.

## 🎯 Objectives
- Monitor parking slot availability in real time.
- Detect vehicle entry and exit using IR sensors.
- Display parking status and current time.
- Enable communication between multiple nodes using CAN.
- Automate parking gate operation using a servo motor.

## 🛠️ Hardware Components
- ARM7 LPC2129 Microcontroller
- IR Sensors
- 20×4 LCD Display
- DS1307 Real-Time Clock (RTC)
- Servo Motor
- CAN Transceiver

## 💻 Technologies Used
- Embedded C
- ARM7 Microcontroller
- CAN Communication Protocol
- I2C Communication Protocol
- UART Communication Protocol
- GPIO and PWM
- Keil µVision IDE
- Proteus Simulation

## ⚙️ System Architecture

### Node 1: Dashboard Node
- Displays available parking slots and current time.
- Shows parking and gate status.
- Receives information through CAN communication.

### Node 2: RTC Node
- Uses the DS1307 RTC to obtain real-time information.
- Communicates with the RTC using I2C.
- Sends time information to the dashboard through CAN.

### Node 3: Gate Control Node
- Receives gate control commands through CAN.
- Controls the servo motor to open and close the gate.

## 🔄 Working Principle
1. IR sensors detect vehicle entry and exit.
2. The system updates the available parking slot count.
3. The dashboard displays the current parking status.
4. The RTC provides current time information through I2C.
5. CAN communication transfers information between the nodes.
6. The gate control node operates the servo motor according to received commands.

## ✨ Key Features
- Real-time parking slot monitoring
- Vehicle entry and exit detection
- CAN-based multi-node communication
- RTC integration using I2C
- Automatic gate control
- LCD-based status display

## 📚 Skills Demonstrated
- Embedded C Programming
- ARM7 LPC2129 Programming
- CAN Protocol Implementation
- UART and I2C Communication
- Sensor and LCD Interfacing
- RTC Interfacing
- PWM and Servo Motor Control
- Firmware Development and Debugging

## 👨‍💻 Author
**Vickey Tyagi**

**Domain:** Embedded Systems

**Technologies:** ARM7 | LPC2129 | Embedded C | CAN | I2C | UART | IR Sensors | PWM

---
*This project demonstrates the application of embedded systems and CAN communication in automated parking management.*
