# Women Safety System (Resue Her)

## Overview
The **Women Safety System** is an IoT-based safety solution designed to ensure personal safety. This system integrates various hardware components like **IMU sensors**, **GPS**, **heart rate sensors**, and **temperature sensors**, along with software to trigger emergency alerts and send real-time location and health data.

## Objectives
- **Understand and integrate** an IoT-based safety system with sensors for health monitoring, fall detection, and location tracking.
- **Automatically send alerts** to predefined contacts when the SOS button is pressed or certain safety thresholds are breached.
- **Continuous health monitoring** of heart rate and body temperature, with real-time alerts when abnormal readings are detected.
- **Fall detection** using IMU sensors that trigger an emergency alert when a fall is detected.
- **Real-time location tracking** via GPS and communication of sensor data using the Blynk platform.

## Hardware Components
- **IMU Sensor (Inertial Measurement Unit)**: For detecting falls based on XYZ acceleration.
- **IR Proximity Sensor**: For detecting the presence of nearby objects or obstacles.
- **GPS Module**: For real-time location tracking.
- **Heart Rate Sensor (Pulse Sensor)**: To monitor heart rate in beats per minute (BPM).
- **Temperature Sensor (e.g., DHT11 or LM35)**: To measure body temperature.
- **NodeMCU (ESP8266)**: Microcontroller to manage all sensor data and connect to the Blynk platform for IoT communication.

## Software Requirements
- **Arduino IDE**: Used for writing and uploading the code to NodeMCU (ESP8266).
- **Blynk Platform**: Used to communicate real-time data and send alerts.

## Block Diagram (Note: Please refer the Report PDF for Block Diagram)
The system consists of:
1. **SOS Push Button**
2. **Heart Rate Sensor**
3. **GPS Module**
4. **Body Temperature Sensor**
5. **IMU Sensor**
6. **NodeMCU (ESP8266)** for controlling and communicating the data via the internet.

The data from all these sensors are transmitted to the **Blynk platform** and email for real-time monitoring and alert notifications.

## How It Works
- The **SOS button** sends a signal in case of an emergency, triggering an immediate alert.
- **Health monitoring** is continuously done through the heart rate sensor and temperature sensor.
- **Fall detection** is managed by the IMU sensor, and if a fall is detected, an alert is sent.
- The system sends **real-time location data** using the GPS module to a Blynk dashboard and predefined contacts.
- The **Blynk platform** helps in managing and visualizing all data and triggering alerts.

## Conclusion
The **Women Safety System** is a comprehensive, reliable, and real-time safety system that uses IoT to ensure the well-being of women. It provides instant alerts, location tracking, and health monitoring, making it a valuable tool for personal safety.

