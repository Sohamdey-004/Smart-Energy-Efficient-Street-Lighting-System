# Smart Energy-Efficient Street Lighting System 🌱💡

## Overview
This project implements an intelligent street lighting system that reduces energy consumption by adapting light intensity based on environmental conditions and vehicle presence.

The system combines passive motion sensing with active distance sensing to ensure reliable illumination even for stationary vehicles.

## Features
- Day/Night detection using LDR
- Adjustable threshold using potentiometer
- Motion detection using PIR sensor
- Active vehicle presence detection using ultrasonic sensor (0–400 cm)
- PWM-based brightness control
- Real-time LCD status display
- Simulated using Tinkercad

## Circuit Diagram
See `circuit/tinkercad_circuit.png`

## Block Diagram
See `circuit/block_diagram.png`

## How It Works
- Daytime → Light OFF
- Night + no vehicle → DIM light
- Night + vehicle/motion → FULL brightness

## Applications
- Smart cities
- Energy-efficient street lighting
- Traffic-sensitive illumination

## Future Scope
- Replace ultrasonic sensor with ToF sensor (VL53L0X)
- Solar-powered operation
- Wireless monitoring

## Author
Srijita Patra
Soham Dey
Abhradeep Adhikari
