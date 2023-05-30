# Code Cadets Extension Racer 2023 🏎️

The project utilises a NodeMCU board and an async web server to control a remote-controlled car. Through pulse width modulation, the NodeMCU communicates with the car, enabling precise movements. Currently, the focus is on implementing remote control via the web server, with plans to add crash detection and autonomous driving capabilities. This project showcases the integration of hardware and software, demonstrating the potential of IoT technologies in remote control systems.

## 📚 Documentation

[Documentation](https://rcracer.codecadets.com/) (This requires an SSO login)

## 📦 Run this Project Locally

- Fork this repository
- Open Project in Arduino IDE
- Install Drivers and required Libraries
- Change network settings to your local network
- Wire up your Board to your car chasis, and launch web server

## ⚡ Wiring Diagram

![Wiring Diagram](wiringDiagram.png)

## 🧱 Dependencies and Libraries
- Arduino
- NodeMCU ESP8266
- ESP8266 WiFi Library
- Arduino JSON Library
- Servo Library
- ESP8266 Async Web Serber Library
