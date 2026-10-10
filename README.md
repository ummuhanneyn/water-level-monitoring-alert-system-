# Water Level Monitoring & Alert System

An IoT prototype that monitors water levels and gives local status indicators plus remote alerts. Built as my final-year project for the BSc in Information Technology and Systems at Mzumbe University (2026).

## Features
- Measures water level using an ultrasonic sensor
- Shows three states in real time: **low, medium and full**
- Local indicators: LCD display, LEDs and a buzzer
- Remote monitoring and alerts through a Blynk mobile dashboard over Wi-Fi (ESP8266)
- Buzzer alert when the tank is full and when it is low

## Hardware Components
- Arduino Uno
- Ultrasonic sensor
- ESP8266 Wi-Fi module
- LCD display
- LEDs
- Buzzer
- Resistors
- Breadboard
- Power supply

## How It Works
1. The ultrasonic sensor measures the distance to the water surface.
2. The Arduino converts the distance into a water level: low, medium or full.
3. The LCD, LEDs and buzzer show the status locally.
4. The ESP8266 sends the status to the Blynk app, which shows it and sends alerts to my phone.

## Project Structure
- code/ : Arduino source code
- images/ : prototype photos, wiring diagram, Blynk dashboard screenshots
- docs/ : project report and documentation

## Setup
1. Install the Arduino IDE and the Blynk library.
2. Open the .ino file in the code folder.
3. Replace YOUR_WIFI_NAME, YOUR_WIFI_PASSWORD and YOUR_BLYNK_TOKEN with your own details.
4. Upload the code to the Arduino Uno and power the circuit.

## What I Learned
IoT prototyping, sensor integration, embedded programming, wireless connectivity and system testing.

## Author
Amina Nurdin Amour
GitHub: github.com/ummuhanneyn
Email: aminaamour03@gmail.com
