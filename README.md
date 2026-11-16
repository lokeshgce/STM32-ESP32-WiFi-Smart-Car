# STM32-ESP32-WiFi-Smart-Car
Custom STM32G431CBT-based WiFi smart car PCB featuring an ESP32-C3-WROOM-02 module for wireless control, LIS3DH accelerometer for tilt detection, dual TB6612FNG motor drivers for four-motor control, and an STDC14 connector for STM32 programming and debugging. Designed using KiCad.


## Project Overview

This project focuses on the design and development of a custom PCB-based WiFi-controlled smart car using the STM32G431CBT microcontroller and ESP32-C3-WROOM-02 WiFi module. The system enables wireless vehicle control and integrates an LIS3DH accelerometer to monitor the vehicle's tilt angle in real time.

Two TB6612FNG motor driver ICs are used to control four DC motors, providing movement in different directions. When the detected tilt angle exceeds a predefined threshold, the STM32 triggers a buzzer alert to indicate a potentially unsafe vehicle position.

The complete hardware circuit and PCB layout are designed using KiCad, with an STDC14 connector provided for STM32 programming and debugging.

The project aims to combine wireless control, embedded system design, motor control, and tilt-based safety monitoring in a compact custom-designed PCB.


## Key Features

- **Advanced Microcontroller:** Powered by the STM32G431CBT high-performance microcontroller for efficient processing and real-time control.
- **Industrial-Standard Hardware Design:** Custom PCB designed using KiCad, incorporating dedicated motor drivers, sensor interfaces, and an STDC14 programming and debugging connector.
- **Tilt-Based Safety Monitoring:** LIS3DH accelerometer continuously monitors vehicle inclination and triggers an automatic buzzer alert when the tilt exceeds a predefined safety threshold.
- **High-Altitude Terrain Safety:** Designed with a tilt-monitoring safety concept to help identify potentially unsafe vehicle inclinations while driving on steep and uneven terrain.
- **WiFi Connectivity:** ESP32-C3-WROOM-02 module enables wireless communication, internet connectivity, and data sharing.
- **Four-Motor Drive System:** Two TB6612FNG motor driver ICs provide independent control of four DC motors.
- **Integrated Embedded Architecture:** Combines wireless communication, real-time sensor monitoring, motor control, and safety alerts in a single custom PCB.


## Hardware Components

| S.No | Component | Description |
|---|---|---|
| 1 | **STM32G431CBT** | High-performance ARM Cortex-M4 microcontroller used as the main controller for sensor processing, motor control, and system operations. |
| 2 | **ESP32-C3-WROOM-02** | WiFi module used for wireless communication, internet connectivity, and data sharing. |
| 3 | **LIS3DH Accelerometer** | Three-axis MEMS accelerometer used to measure vehicle acceleration and monitor tilt or inclination for safety alerts. |
| 4 | **TB6612FNG Motor Driver (2 Nos.)** | Dual-channel DC motor driver ICs used together to control four DC motors with bidirectional speed control. |
| 5 | **STDC14 Connector** | Standard 14-pin debugging and programming interface used for STM32 development through compatible ST-LINK tools. |
| 6 | **Buzzer** | Provides an audible warning when the vehicle's tilt exceeds the predefined safety threshold. |
| 7 | **Decoupling Capacitors** | Help reduce supply noise and voltage fluctuations, ensuring stable operation of electronic components. |

### Main Hardware Architecture

- **Processing Unit:** STM32G431CBT
- **Wireless Communication:** ESP32-C3-WROOM-02
- **Tilt Detection:** LIS3DH
- **Motor Control:** 2 × TB6612FNG
- **Programming and Debugging:** STDC14


## System Architecture

<img width="1536" height="1024" alt="Smart Car System Architecture" src="https://github.com/user-attachments/assets/58e4e887-5b24-4e77-943a-939d34d029fe" />


## Circuit Design

<img width="814" height="550" alt="Screenshot 2026-10-08 235948" src="https://github.com/user-attachments/assets/9a69aaf6-a6ed-4454-bc5f-2281662c568f" />


## PCB Design

### Top Layer

<img width="502" height="551" alt="Screenshot 2026-11-16 185503" src="https://github.com/user-attachments/assets/f3004651-54da-41a5-8be5-d4a33457a67a" />

### 3D View

<img width="433" height="394" alt="image" src="https://github.com/user-attachments/assets/de882b12-8f03-453d-8f78-0f985d111309" />


## Software and Tools

The following software tools are used for hardware design, PCB development, firmware programming, and system testing.

| Software / Tool | Purpose |
|---|---|
| **KiCad** | Schematic capture, component placement, PCB routing, and 3D PCB visualization. |
| **STM32CubeIDE** | STM32G431CBT firmware development, compilation, debugging, and programming. |
| **STM32CubeMX** | Microcontroller configuration, GPIO setup, clock configuration, and peripheral initialization. |
| **Arduino IDE** | ESP32-C3-WROOM-02 firmware development and WiFi communication programming. |
| **ST-LINK** | Programming and debugging the STM32 microcontroller through the STDC14 interface. |

### Design and Development

- **Hardware Design:** KiCad
- **Microcontroller Programming:** STM32CubeIDE
- **Wireless Communication:** ESP32 development environment
- **Programming and Debugging:** ST-LINK


## Future Improvements

- **Obstacle Detection:** Integrate ultrasonic or LiDAR sensors to detect obstacles and improve vehicle navigation and driving safety.

- **Mobile Application Integration:** Develop a dedicated mobile application for wireless vehicle control, live status updates, and remote monitoring.

- **Cloud-Based Data Monitoring:** Implement cloud connectivity to store, visualize, and analyze vehicle data, including tilt measurements and operational parameters, for remote monitoring.


## 12. Author
Lokesh A
Electronics and Communication Engineering





