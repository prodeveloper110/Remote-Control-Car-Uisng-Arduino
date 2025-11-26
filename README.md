Bluetooth-Controlled RC Car with Arduino Uno
Project Overview
This repository contains the complete code and documentation for a Bluetooth-controlled RC car built using Arduino Uno. Developed by Shahid Rafiq (@shahid407) and my team, this DIY project demonstrates hands-on embedded systems programming, motor control, and wireless communication. It's perfect for hobbyists, students, and makers exploring IoT and robotics.
Key Components:

Microcontroller: Arduino Uno
Motor Driver: L298 for controlling DC motors and wheel movements
Bluetooth Module: HC-05 for wireless connectivity
Control App: Sritu Hobby app (Android/iOS) for remote operation
Chassis: Transparent acrylic base with four wheels for easy prototyping

Features:

Forward, backward, left, right, and stop controls via Bluetooth
Smooth speed adjustment and precise steering
Low-cost build (under $50 in parts)
Extensible for additions like obstacle avoidance (ultrasonic sensors) or line following

How It Works:

Hardware Setup: Connect the L298 motor driver to Arduino pins for PWM speed control. Wire HC-05 to serial pins (TX/RX) for Bluetooth pairing.
Software: The Arduino sketch (rc_car.ino) handles Bluetooth commands from the Sritu Hobby app, parsing inputs to drive motors.
App Integration: Use the app's joystick interface to send serial commands like 'F' for forward.
