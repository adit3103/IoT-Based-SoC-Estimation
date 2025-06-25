# IoT-Based State of Charge (SoC) Estimation of a Battery Cell

This project estimates the State of Charge (SoC) of a lithium iron phosphate (LiFePO₄) battery using three methods:
- Direct Voltage Mapping
- Coulomb Counting (AHC)
- Kalman Filter (KF)

## 📌 Features
- Real-time monitoring of battery voltage and current
- Live SoC display via I2C LCD and Serial Monitor
- Arduino Uno-based implementation with ACS712 and Voltage Sensor
- MATLAB/Simulink battery behavior modeling
- Cloud-based integration ideas from research papers

## 🔧 Hardware
- Arduino Uno
- ACS712 Current Sensor
- MH Electronics Voltage Sensor
- LiFePO₄ Battery
- 16x2 I2C LCD Display

## 📊 Simulation Tools
- MATLAB/Simulink for battery modeling and SoC estimation accuracy
- Kalman filter used to correct drift in Coulomb Counting

## 📁 Repository Contents
- `main.ino`: Arduino Code
- `Project_Presentation.pptx`: Overview slides
- `circuit.docx`, `cloud soc.docx`, `type of sensor.docx`: Research background
- `/images`: Supporting visual references
- `README.md`: Project summary

## 🧠 References
- [Deep Learning-Based IoT and Cloud-Integrated SOC Estimation](https://www.sciencedirect.com/science/article/pii/S2352152X20308495#sec0002)
- [Kalman Filtering in Battery SOC Estimation](https://www.sciencedirect.com/science/article/abs/pii/S1364032119304332)

