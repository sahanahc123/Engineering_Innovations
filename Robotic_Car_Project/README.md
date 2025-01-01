# Android Application-Based Robotic Car

## Description
The Android Application-Based Robotic Car is a hardware and software-integrated project designed for remote-controlled vehicle navigation. The car is operated via an Android application that communicates with the hardware through Bluetooth technology. This project showcases the application of IoT, robotics, and mobile app control.

## Objectives
- Develop a robotic car controlled by an Android application using Bluetooth communication.
- Enable efficient, wireless control of the car’s movement (forward, backward, left, right, and stop).
- Integrate sensors for obstacle detection and avoidance to ensure safe navigation.
- Demonstrate the seamless interaction between hardware and software systems.

## Hardware Components
- **Chassis**: Provides the base for mounting all components.
- **DC Motors**: Enables the movement of the robotic car.
- **Motor Driver Module (L298N)**: Controls the motors based on commands received.
- **Bluetooth Module (HC-05/HC-06)**: Facilitates wireless communication between the Android app and the car.
- **Arduino Board**: Acts as the microcontroller to process commands and control hardware components.
- **Battery Pack**: Supplies power to the robotic car.
- **Obstacle Detection Sensor (e.g., ultrasonic sensor)**: Ensures safety by detecting and avoiding obstacles.

## Software Requirements
- **Arduino IDE**: For writing and uploading code to the Arduino board.
- **Android Application**: Developed using MIT App Inventor or other app development platforms. Allows users to control the car’s motion via Bluetooth.

## Features
- **Bluetooth-controlled motion** with commands for:
  - Moving forward
  - Moving backward
  - Turning left
  - Turning right
  - Stopping
- **Obstacle detection** and automatic stopping to avoid collisions.
- **User-friendly Android application interface** for seamless control.
- **Cost-effective and energy-efficient design**.

## Block Diagram(Refer Report PDF)

## Working Mechanism
1. The Android application sends control signals via Bluetooth.
2. The Bluetooth module receives these signals and forwards them to the Arduino.
3. The Arduino processes these commands and activates the motor driver.
4. The motor driver controls the movement of the motors based on the received commands.
5. If an obstacle is detected, the Arduino stops the car and alerts the user via the app.
