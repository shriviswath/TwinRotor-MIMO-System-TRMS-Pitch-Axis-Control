# TwinRotor-MIMO-System-TRMS-Pitch-Axis-Control
Twin Rotor MIMO System (TRMS) project focused on pitch-axis control using PID and LQR algorithms. Implemented in C language on the Tiva C Series TM4C123GXL LaunchPad using Code Composer Studio. Performance was analyzed by comparing tracking accuracy, stability, and response, where LQR showed better control than PID.

## 📌 Overview
This project focuses on controlling the **Pitch Axis** of a Twin Rotor MIMO System (TRMS) using **PID** and **LQR** control algorithms.  
The system was implemented in **C language** on the Tiva C Series TM4C123GXL LaunchPad.

## ⚙️ Hardware Used
- Tiva C Series TM4C123GXL LaunchPad  
- MPU6050 IMU Sensor  
- SimonK ESC (30A) + BLDC Motors  
- TRMS Mechanical Setup  
- 3S LiPo Battery  

## 💻 Software Used  
- Embedded C Language  
- TivaWare Driver Library
- Code Composer Studio 12.8.1
- VS Code 

## 🚀 Features
- Real-time pitch angle sensing using MPU6050  
- PID control implementation  
- LQR control implementation  
- PWM motor speed control  
- Telemetry monitoring through UART  
- Emergency stop function  

## 📊 Results
Both controllers were tested for pitch stabilization.  
LQR showed:
- Better stability  
- Faster settling time  
- Lower overshoot  
- Improved tracking accuracy  

## 📂 Repository Contents

### 📁 Code
- `LQR_Code` – C program for pitch control using Linear Quadratic Regulator (LQR)
- `PID_Code` – C program for pitch control using Proportional Integral Derivative (PID)
- `PWM Calculator With IMU` – PWM control and IMU sensor integration utility code

### 📁 Resources
  - TRMS Response Graph – Experimental graphs, response plots, and controller performance comparison
  - STRUCTURAL AND MATERIAL ANALYSIS OF TRMS
  - TRMS Hardware Data
  - TRMS_Project_Documnetation
  - Theoretical Transfer Func (Pitch&Yaw)
  - Transfer Function (OLD Report-2017)

### 📁 Sample Data Output
- `LQR Output` 
- `PID Output` 

### 📄 Main File
- `README.md` – Project documentation and overview

## 🎯 Future Scope
- Add yaw axis control  
- Full MIMO TRMS control  
- Advanced state estimation  
- Real-time GUI monitoring  

## 👨‍💻 Author
Shri Viswath C K


Reference Video Output:



https://github.com/user-attachments/assets/1eec3415-6f89-4cee-8fbb-2949557dd089



https://github.com/user-attachments/assets/083462d4-90bc-4063-882e-7b2a33bc7ae3




