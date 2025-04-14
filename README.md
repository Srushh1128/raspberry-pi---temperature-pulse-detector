# raspberry-pi---temperature-pulse-detector
Temperature and Pulse Rate Detector using Raspberry Pi is a health monitoring system that measures real-time body temperature and pulse rate using digital sensors connected to a Raspberry Pi. This project is designed to demonstrate how embedded systems and IoT can be used in basic healthcare monitoring applications. 

# Temperature and Pulse Rate Detector using Raspberry Pi

This project uses a Raspberry Pi to detect and display human body temperature and pulse rate using connected sensors.

## Features
- Reads temperature using a DHT11 or LM35 sensor.
- Reads pulse rate using a Pulse Sensor.
- Displays real-time readings via terminal or GUI (Tkinter optional).
- Easy to set up and run on Raspberry Pi.

## Hardware Used
- Raspberry Pi 3/4
- DHT11/LM35 Temperature Sensor
- Pulse Sensor (KY-039 / other)
- Jumper Wires
- Breadboard

## Software Requirements
- Python 3
- GPIO Library (RPi.GPIO)
- Adafruit_DHT (if using DHT11)
- Matplotlib (optional for graph)

## Setup
```bash
pip install -r requirements.txt
python3 main.py
