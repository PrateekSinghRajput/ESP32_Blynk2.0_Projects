# ESP32_Blynk2.0_Projects

## Overview
This repository contains projects demonstrating the use of ESP32 microcontroller with the Blynk 2.0 IoT platform. The main example project is "Esp32_LedBlink_Using_Blynk2.0_App," which shows how to control an LED connected to ESP32 via the Blynk app using WiFi.

## Features
- Control ESP32 GPIO pins remotely using the Blynk 2.0 mobile app.
- Demonstrates IoT connectivity with Blynk templates and virtual pins.
- Simple LED blink control example using Blynk widgets.
- Code written in C++ using Arduino framework.

## Getting Started

### Prerequisites
- ESP32 development board.
- Arduino IDE installed.
- Blynk 2.0 account (Register from https://blynk.cloud).
- USB cable for ESP32 connection.
- Installed libraries:
  - Blynk library for ESP32
  - WiFi library

### Setup Blynk Project
1. Create a new template on [Blynk.Cloud](https://blynk.cloud/dashboard).
2. Select hardware as ESP32 and connection type as WiFi.
3. Create virtual pins and datastreams for controlling and monitoring.
4. Copy your `BLYNK_TEMPLATE_ID`, `BLYNK_DEVICE_NAME`, and `BLYNK_AUTH_TOKEN`.

### Coding and Upload
1. Open Arduino IDE.
2. Install ESP32 board support via Board Manager.
3. Install required libraries (Blynk, WiFi).
4. In the provided Arduino sketch, update:
5. Connect ESP32 to your PC via USB.
6. Select the appropriate ESP32 board and port.
7. Upload the code.

### Usage
- Open the Blynk 2.0 app.
- Connect using the authorized template and device.
- Use the control widgets (buttons, sliders) configured on the app dashboard to control the ESP32 pins and peripherals like an LED.

## Project Structure
- `src/` - Arduino sketch files
- `README.md` - Project documentation

## Troubleshooting
- Ensure correct board and port are selected in Arduino IDE.
- Use data-capable USB cable.
- Check WiFi credentials.
- Verify Blynk template credentials are correct.
- Restart Blynk app and ESP32 if connection fails.

