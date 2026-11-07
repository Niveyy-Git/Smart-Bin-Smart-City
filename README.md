# SMART BIN FOR SMART CITY – INDUSTRY 4.0

## Project Overview
An IoT-based automatic smart waste management system developed using Arduino UNO.

The system automatically opens the dustbin lid, identifies wet and dry waste, separates waste into different compartments and compresses dry waste to improve storage efficiency.

## Features
- Automatic lid opening and closing using ultrasonic sensor.
- Wet and dry waste segregation using a moisture sensor.
- Separate wet and dry waste compartments.
- Automatic dry waste compression using a DC motor.
- Independent waste-level monitoring.
- GSM-based SMS alerts when either compartment is full.
- Fire detection and buzzer alert.
- PIR-based movement detection.

## Hardware Components
- Arduino UNO
- Ultrasonic sensors
- Soil moisture sensor
- Servo motors
- DC motor
- L298N motor driver
- SIM800L GSM module
- Flame sensor
- PIR sensor
- Buzzer
- Limit switches

## Software Used
- Arduino IDE
- Embedded C/C++
- GSM communication
- Sensor-based automation

## Working Principle
The ultrasonic sensor detects a person and opens the lid automatically. After waste is deposited, the moisture sensor identifies whether it is wet or dry. The sorting mechanism directs the waste into the appropriate compartment.

Dry waste is sent to a separate compression chamber. Ultrasonic sensors monitor both compartments. When either compartment becomes full, the GSM module sends an SMS notification to the waste collection team.

## Applications
- Smart cities
- Public waste management
- Residential waste collection
- Automated waste segregation

## Project Outcome
Designed to improve waste segregation, reduce dry waste volume, monitor bin capacity and support timely waste collection.

