# AutomaticGateDemoKit

This project demonstrates an automatic gate system using an Arduino Uno. The system uses an ultrasonic sensor to detect approaching objects. When an object is detected within 50 cm, the gate (servo motor) opens, a blue LED lights up, and a buzzer beeps intermittently. After 5 seconds of no detection, the gate closes and a red LED indicates the gate is locked.

## Features:
- Ultrasonic object detection
- Servo motor-controlled gate
- Visual indicators (Red/Blue LEDs)
- Audio feedback via buzzer
- Auto-close after timeout

## Components:
- Arduino Uno
- Ultrasonic Sensor (HC-SR04)
- Servo Motor (SG90 or similar)
- Red and Blue LEDs
- Buzzer
