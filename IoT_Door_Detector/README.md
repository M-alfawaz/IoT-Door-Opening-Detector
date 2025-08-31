# IoT Door Opening Detector 🚪🔔

## Project Overview
An **ESP32-based IoT door monitoring system** using an **IR motion sensor (FC-51)** to detect door activity, a **buzzer** for audible alerts, and **LEDs** for visual status.  
The project integrates with **Arduino IoT Cloud** for real-time monitoring and remote control.

## Components Used
- ESP32 Dev Module
- FC-51 IR Sensor
- Buzzer
- Green LED
- Blue LED
- Breadboards (x2) and jumper wires

## Features
- Real-time door activity detection via IR sensor
- Buzzer + LED alerts on trigger
- Arduino IoT Cloud integration (remote monitoring and control)
- Cloud property callback to toggle LED state

## How to Run
1. Open `src/door_detector.ino` in Arduino IDE or Arduino Cloud Web Editor.
2. Configure Arduino IoT Cloud (Device, Thing, Variables) and generate `thingProperties.h`.
3. Wire IR sensor, buzzer, and LEDs to the ESP32 as defined in the code.
4. Upload the sketch and use the IoT Cloud dashboard to monitor/control.

## Documentation
See [`docs/IoT_Door_Detector.pdf`](docs/IoT_Door_Detector.pdf) for the full report.
