# Electronic-Safety-Device-for-Door-Lock-with-Raspberry-Pi-PICO

**Abstract**
This project simulates an Electronic Safety Device for Door Locks using the Raspberry Pi PICO microcontroller on the Wokwi platform. It integrates keypad-based authentication and simulated servo motor control to enhance security and provide convenient access control in various simulated environments.

**Table of Contents**
Introduction
Literature Survey
Methodology & Approach
Simulation & Results
Inferences & Recommendations
Setup Instructions
Usage
References

**Introduction**
This project is a simulated implementation of an electronic door locking system using the Raspberry Pi PICO microcontroller. The system is designed to offer enhanced security with keypad-based authentication and servo motor control. The project was developed on the Wokwi simulation platform, which allows for testing and refinement in a virtual environment.

**What is Embedded Systems?**
Embedded systems are specialized computing systems designed for dedicated functions within larger systems or devices. They are integral to various industries, from automotive to consumer electronics and healthcare.

![Screenshot 2024-08-22 210122](https://github.com/user-attachments/assets/85bc71f0-2a5c-4b62-bf33-19015fa094dd)

**Applications of Embedded system**

![Screenshot 2024-08-22 210910](https://github.com/user-attachments/assets/bd1c21b5-83ae-47df-badd-0a604da67061)

**Block Diagram of the Embedded Systems**

![Screenshot 2024-08-22 210307](https://github.com/user-attachments/assets/21e3b338-9240-45e9-bd54-93ad58b82a39)

**Literature Survey**
The literature survey covers the study of various home automation technologies, security protocols, and the programming of microcontrollers like Raspberry Pi. It also addresses energy efficiency, security concerns, and user interface design in embedded systems.

**Methodology & Approach**
The project methodology includes:
Research and Planning: In-depth research on electronic door locking mechanisms and Raspberry Pi PICO capabilities.
Component Selection: Identifying and selecting components compatible with Raspberry Pi PICO and the Wokwi platform.
Circuit Design: Developing the circuit layout for proper connectivity.
Programming: Writing and testing the firmware for Raspberry Pi PICO.
Simulation and Testing: Using Wokwi for virtual simulation and testing the system's functionality.

**Block Diagram**

![Screenshot 2024-08-22 211044](https://github.com/user-attachments/assets/f2217ce8-8bb8-411b-bcce-b3609a50bb35)

**Reference Simulation Diagram**

![Screenshot 2024-08-22 211100](https://github.com/user-attachments/assets/04851978-eebb-4d9e-8f5f-fb8449517708)


**Components Used**
Wokwi Pi PICO
Wokwi LCD 1602
Wokwi Membrane Keypad
Wokwi Servo Motor

**Figure Wokwi Pi PICO**

![Screenshot 2024-08-22 211112](https://github.com/user-attachments/assets/1a332f69-adba-407e-8172-0d39911dc00b)

**Figure of Wokwi LCD 1602**

![Screenshot 2024-08-22 211227](https://github.com/user-attachments/assets/3caf2157-18ff-4a95-99a3-29dbd2c83fe4)

**Figure of Wokwi Membrane Keypad**

![Screenshot 2024-08-22 211141](https://github.com/user-attachments/assets/623e64cd-ca18-4c02-a1c7-c98e97da4446)

**Figure of Wokwi Servo Motor**

![Screenshot 2024-08-22 211234](https://github.com/user-attachments/assets/e0a3a5a9-9b38-4131-b423-79d2ff402194)

**Simulation & Results**
Detail the outcomes of your simulation, including the successful integration of keypad authentication and servo control. Discuss any challenges faced during simulation and how they were resolved.



**Setup Instructions**
Clone the repository.
Open the project on the Wokwi platform.
Follow the instructions provided in the simulation_config.json file for component setup.
Upload the provided code to the Raspberry Pi PICO within the simulation environment.

**Usage**
Input the passcode using the membrane keypad.
The servo motor will unlock or lock the door based on the correct passcode input.
The LCD displays the current status (Locked/Unlocked).

**References**
Wokwi Platform Documentation
Raspberry Pi Pico Documentation
