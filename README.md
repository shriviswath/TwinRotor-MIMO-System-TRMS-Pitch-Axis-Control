# TwinRotor-MIMO-System-TRMS-Pitch-Axis-Control
Twin Rotor MIMO System (TRMS) project focused on pitch-axis control using PID and LQR algorithms. Implemented in C language on the Tiva C Series TM4C123GXL LaunchPad using Code Composer Studio. Performance was analyzed by comparing tracking accuracy, stability, and response, where LQR showed better control than PID.

## 📌 Overview
This project focuses on controlling the **pitch axis** of a Twin Rotor MIMO System (TRMS) using **PID** and **LQR** control algorithms.  
The system was implemented in **C language** on the Tiva C Series TM4C123GXL LaunchPad using :contentReference[oaicite:1]{index=1}.

## ⚙️ Hardware Used
- Tiva C Series TM4C123GXL LaunchPad  
- MPU6050 IMU Sensor  
- ESC + BLDC Motors  
- TRMS Mechanical Setup  
- Power Supply / Battery  

## 💻 Software Used
- :contentReference[oaicite:3]{index=3}  
- Embedded C Language  
- TivaWare Driver Library  

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
- `PID_Code.c` – Pitch control using PID  
- `LQR_Code.c` – Pitch control using LQR  
- `README.md` – Project documentation  

## 🎯 Future Scope
- Add yaw axis control  
- Full MIMO TRMS control  
- Advanced state estimation  
- Real-time GUI monitoring  

## 👨‍💻 Author
Shri Viswath C K
