

# Obstacle-Avoiding Robot with Voice Control

This project involves creating an obstacle-avoiding robot that can navigate autonomously and respond to voice commands. It utilizes an ultrasonic sensor to detect obstacles and servo motors for scanning the environment. The robot's movement is controlled using an Arduino Uno and C++ code in the Arduino IDE.

## Features
- **Obstacle Avoidance**: The robot autonomously detects and avoids obstacles using an ultrasonic sensor.
- **Voice Control**: The robot can receive voice commands for basic movement (if integrated with a voice recognition module).
- **Autonomous Navigation**: The robot moves forward, backward, and turns left or right based on detected obstacles.
- **Servo Scanning**: The servo motor scans the environment to detect obstacles on the left and right sides.

## Components
- **Arduino Uno**: Microcontroller used to control the robot.
- **HC-SR04 Ultrasonic Sensor**: Measures the distance to obstacles.
- **Servo Motor**: Scans the surroundings for obstacles.
- **L298N Motor Driver**: Controls the motors for movement.
- **DC Motors**: Drives the robot forward and backward.
- **Voice Recognition Module**: Allows the robot to respond to voice commands (optional).

## Technologies Used
- **C++ (Arduino IDE)**: Programming language used to control the robot's logic.
- **Servo Library**: Library used to control the servo motor.
- **NewPing Library**: Library used to interface with the ultrasonic sensor for distance measurement.
- **Arduino IDE**: Software used to program the Arduino.



2. **Install necessary libraries**:
   - Servo library
   - NewPing library
   (Install through Arduino IDE Library Manager)

3. **Upload the code to Arduino**:
   - Open the `robot.ino` file in the Arduino IDE.
   - Select the correct board and port in the **Tools** menu.
   - Click **Upload** to program the Arduino Uno.

4. **Wiring**:
   Follow the wiring instructions in the project description to connect all components:
   - Connect the ultrasonic sensor to the Arduino.
   - Wire the motors and L298N motor driver to the Arduino.

## Usage
1. Power the robot.
2. It will move forward autonomously and avoid obstacles using the ultrasonic sensor.
3. If an obstacle is detected, the robot will stop, reverse, and choose a new direction based on available space.

