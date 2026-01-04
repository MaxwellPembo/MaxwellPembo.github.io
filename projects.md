# Projects


## Table of Contents
#### Embedded Systems & Firmware
- [ToolSense – IoT-Based Smart Workshop Management System](#toolsense---iot-based-smart-workshop-management-system)
- [Arduino Robot – Kernel Level Wall Following Robot](#arduino-robot---wall-following-robot)
- [SkyBeam – Point to Point Drone Communication](#skybeam---point-to-point-drone-communication)

#### FPGA Design
- [FPGA Oscilloscope and Function Generator](#fpga-oscilloscope-and-function-generator)
- [FPGA Mock Space Invaders Game](#fpga-mock-space-invaders-game)
- [FPGA 16-bit Processor](#fpga-16-bit-processor)

---

## ToolSense - IoT based Smart Workshop Management System
**Reasoning:** Final Project for IoT Class  
**Technologies:** 
- ESP32
- ESP32-Cam
- Raspberry Pi
- C++
- React.js
- Python
- **Azure IoT Hub**

**Description:**  
ToolSense is a smart workshop management system that tracks the live status of toolboxes and their contents. It combines sensors and modules to recognize faces from a registered group of users and track tools as they are taken or returned. The system maintains a live feed of toolbox status for administrators via a web application. ToolSense was built using **Internet of Things strategies and resources**.

**What I demonstrated:**
- **Embedded Systems Design:** Implemented multiple embedded system features including facial detection and encoding, integration of hardware sensors, and system-to-system Wi-Fi communication.  

- **IoT Cloud Integration:** Leveraged **Azure IoT Hub** for real-time telemetry storage and monitoring.  

- **Scripting and Backend Development:** Used Python, C#, and React.js to instantaneously send and collect data from the cloud for use in the user interface.


**Images:**
![SystemArchtecture](/Items/Images/ToolSense/Slide1.png)
*ToolSense System Design*

![DrawerPicture](/Items/Images/ToolSense/Drawer.png)
*ToolSense Drawer Module*

![UserInterface](/Items/Images/ToolSense/ToolStatus.png)
*ToolSense User Interface*


**GitHub:** https://github.com/MaxwellPembo/ToolSense

---

## Arduino Robot - Wall Following Robot

**Reasoning:** Project for Embedded Systems Class.
**Technologies:** 
- Arduino Uno
- C++

**Description:**  
This project included created a fully automatic, self driving robot that followed a wall while avoiding obsticals in its path. An Arduino Uno was used with motor drivers, Ultrasonic Sensors, Servos, and IR Recvivers to create the system that observed the robots surroundings and make movement decisions. The robot also holds a remote contoled functionlity, where the moverments are driven by an IR remote. All firmware was written at the register level and no expternal Ardino lobraries were used.

**What I demonstrated:**
- **Register Level Programming**: Coded all functions at register level without using aruduino libraries. 

- **Hardware Interfacing**: Used a combonation of Ultrasonic senors, Servos, Motors, and IR recivers. 

- **Timer & Interupt Configuration**: Configured my own timers, counters, and PWM signals to drive system logic.

**Images:**
![RobotFritz](/Items/Images/ArdunioRobot/CircuitDiagram.png)
*Robot System Design*

![RobotFritz](/Items/Images/ArdunioRobot/FinishedRobot.jpeg)
*Finished Robot*

**GitHub:** https://github.com/MaxwellPembo/Arduino-Robot

---

## SkyBeam - Point to Point Drone Communication


**Reasoning:** Senior Project 
**Technologies:** 
- ESP32
- C++
- Python
- mmWave (60 GHz) Systems

**Description:**  
SkyBeam is a project focused on maintaining a **60 GHz communication link** between a stationary base station and a moving drone using **beamforming** to track the system’s movement. The system tracks the drone’s location based on antenna data and adjusts antenna gimbals in real time to maintain the connection. The system includes multiple servos that are driven automatically using antenna data, manually using a joystick, or remotely through a Bluetooth application.


**What I demonstrated:**
- **mmWave Communication**: Levraged Beamforming and beam-tracking techniques for maintaing a communication link.

- **Firmware Development**: Implemented C++ code to process antenna data and track moving drone.

- **System Control**: Developed precise logic that adjusted beam direction.

**Video:**
**[Functionality Video](https://unl.yuja.com/V/Video?v=14783007&node=63450853&a=15950506)**

---

## FPGA Oscilloscope and Function Generator
**Reasoning:** Advanced Embedded Systems Project
**Technologies:** 
- VHDL
- Nexus Video FPGA
- C
- Xilinx Vivado
- MicroBlaze Soft Processor
 
**Description:**  

This project consisted of implementing a Oscilloscope and function generator using VHDL on a FPGA board. This system used custom digital logic componets and a **MicroBlaze soft processor**. Logic was created to drive a VGA/HDMI video output at 640x480 resolution, that showed the inputted signal. System functionality is driven using on board buttons and commands read though **UART**.

**What I demonstrated:**
- **FPGA Design**: Developed digital logic using VHDL and Xilinx Vivado.

- **Testing & Verification**: Tested functionality using testbench simulations and hardware testing. 

**Images & Videos**
**![SystemDesign](/Items/Images/OScope/GC_1.2.png)**
*System Design*

**![Diagram](/Items/Images/OScope/newGC1.png)**
*Block Diagram*

**![Functionality_oScope](/Items/Images/OScope/GC_1.png)**
*O-Scope Functionality*

**[Oscilloscope Functionality Video 1](https://www.youtube.com/watch?v=GC_lx_L3_Rk)**
**[Oscilloscope Functionality Video 2](https://www.youtube.com/shorts/oO8TJ-WLmiQ)**
**[Function Generator Function Video](https://www.youtube.com/shorts/6k0h5HHZdU4)**

**GitHub:** https://github.com/MaxwellPembo/FPGA-Oscilloscope

---

## FPGA Mock Space Invaders Game


**Reasoning:** Final Project for Advanced Embedded Systems Class.

**Technologies:** 
- VHDL
- Nexus Video FPGA
- Xilinx Vivado
- NES Controller (5-pin interface)

**Description:**  
This project involved creating a verison of space invaders that ran on a FPGA contolled by a clasic NES controller. The game logic was created using **VHDL** for hardware and video control. User input was read using the boards PMOD interface with a 5-Pin NES contoller. The HDMI port on the FPGA was used to output game video at 60 fps at 640x480 resolution.

**What I demonstrated:**
- **FPGA Design**: Developed digital logic using VHDL and Xilinx Vivado.

- **Testing & Verification**: Tested functionality using testbench simulations and hardware testing. 

- **Peripheral Interfacing**: Created logic system to read signals from external controller.


**Images & Videos**
**![BlockDiagram](/Items/Images/SpaceInvaders/BlockDiagram.png)**
*Block Diagram*

**[Space Invaders Function Video](https://www.youtube.com/watch?v=NFx8UxgBh_o)**


**GitHub:** https://github.com/MaxwellPembo/FPGA-SpaceInvaders

---

## FPGA 16-bit Processor
**Reasoning:** Computer Organization Project

**Technologies:** 
- DE10-Lite FPGA
- VHDL

**Description:**  
This project consited of creating a **16-bit processor with 8 registers** from VHDL on a DE10-Lite FPGA. The processor was able to solve calculations by running assebmly code with hexidecmail encoding. The main components that were consisted of a **Control Unit, ALU, and Register file**.

**What I demonstrated:**
- **FPGA Design**: Developed digital logic using VHDL and Xilinx Vivado.

- **CPU Architecture & Design**: Resarched and Developed a 16-bit processor that was able to run assebmly code. 

**Images & Videos**
**![BlockDiagram](/Items/Images/Processor/BlockDiagramProcessor.png)**
*Block Diagram for Processor*