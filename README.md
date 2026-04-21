# weather-monitoring-esp32
Weather Monitoring System using ESP32 with sensors like DHT11, BMP180, Rain sensor, LDR Sensor, and IoT integration

## WEATHER MONITORING SYSTEM USING ESP32

## Overview of the Project
<p align="justify">
The Weather Monitoring System using ESP32 is an IoT-based project designed to monitor environmental conditions in real time. It collects data such as temperature, humidity, atmospheric pressure, light intensity, and rainfall using various sensors. The ESP32 microcontroller processes this data and sends it to a cloud platform (Blynk IoT), allowing users to monitor weather conditions remotely through a mobile application.This system is especially useful in agriculture, environmental monitoring, and smart city applications.</p>

## Abstract
<p align="justify">
This project presents an innovative weather monitoring system that detects, records, and displays weather parameters like temperature, humidity, pressure, and light intensity. The system uses interconnected sensors to gather real-time data and transmits it to a cloud platform for visualization.The system helps farmers and users make informed decisions regarding irrigation, planting, and harvesting. By integrating ESP32 with Blynk IoT, the system provides remote monitoring capability, making it efficient and user-friendly.</p>

# Introduction
<p align="justify">
Weather monitoring plays an important role in agriculture, disaster management, and environmental studies. Traditional weather stations are expensive and not easily accessible to individuals.With the advancement of IoT technology, low-cost and efficient systems can be developed using microcontrollers like ESP32. This project focuses on building a compact and wireless weather monitoring system that provides accurate and real-time data through sensors and cloud integration.</p>

# Objectives

The main objectives of this project are:<br>
- To design and develop a real-time weather monitoring system using ESP32 microcontroller
- To accurately measure environmental parameters such as:<br>
          -  Temperature<br>
          -  Humidity<br>
          - Atmospheric pressure<br>
          - Light intensity<br>
          - Rainfall detection<br>
- To implement sensor integration and data acquisition from multiple sources
- To display real-time data locally using an LCD display
- To enable wireless data transmission using ESP32’s built-in Wi-Fi
- To integrate the system with Blynk IoT platform for remote monitoring
- To provide user-friendly visualization of data through mobile dashboards
- To develop a low-cost, energy-efficient, and portable system
- To assist farmers and users in making informed decisions based on weather conditions
- To demonstrate the practical application of IoT in environmental monitoring systems

# Components Used<br>
**Hardware Components**<br>
- ESP32 Microcontroller
- DHT11 Sensor (Temperature & Humidity)
- BMP180 Sensor (Pressure)
- LDR Sensor (Light Intensity)
- Rain Sensor
- LCD Display (I2C)
- Power Supply (Battery/Adapter)<br>
**Software Components**<br>
- Arduino IDE
- Blynk IoT Platform<br>

# Description of Components
- **ESP32 Microcontroller**<br>
A powerful microcontroller with built-in Wi-Fi and Bluetooth used for processing and communication.

- **DHT11 Sensor**<br>
Measures temperature and humidity using a thermistor and capacitive humidity sensor.

- **BMP180 Sensor**<br>
Measures atmospheric pressure and temperature, useful for weather prediction.

- **LDR Sensor**<br>
Detects light intensity based on resistance variation.

- **Rain Sensor**<br>
Detects rainfall using conductivity or light interruption principle.

- **LCD Display**<br>
Displays real-time sensor data locally.

- **Cloud Server (Blynk)**<br>
Stores and displays data remotely via mobile app.<br>
# Arduino IDE Setup Instructions
- Download and install Arduino IDE
- Open Arduino IDE
- Go to File → Preferences
- Add ESP32 board URL:<br>
           https://dl.espressif.com/dl/package_esp32_index.json
- Go to Tools → Board → Board Manager
- Search for ESP32 and install
- Select ESP32 Dev Module
- Install required libraries:<br>
          - DHT sensor library<br>
          - Adafruit BMP180 library<br>
          - Blynk library
- Connect ESP32 via USB
- Select correct COM port
- Upload the code
# Blynk IoT Setup Instructions
- Install Blynk IoT app on mobile
- Create an account/login
- Create a new template/project
- Add datastreams for:<br>
            - Temperature<br>
            - Humidity<br>
            - Pressure<br>
            - Rain<br>
            - Light
- Copy Auth Token
- Add widgets (gauges, graphs, etc.)
- Paste Auth Token in Arduino code
- Upload code to ESP32
- Run project and monitor data live<br>
# Working of the Project <br>
<p align="justify">
The working of the weather monitoring system begins with the collection of environmental data through various sensors. The DHT11 sensor measures temperature and humidity, the BMP180 sensor detects atmospheric pressure, the LDR sensor senses light intensity, and the rain sensor identifies rainfall. These sensors continuously gather real-time data from the surroundings.The ESP32 microcontroller acts as the brain of the system. It receives signals from all sensors, processes the data, and converts it into meaningful values. This processed data is then displayed on an LCD screen so users can directly view the readings.</p>
<p align="justify">
At the same time, the ESP32 uses its built-in Wi-Fi to transmit the data to the Blynk IoT cloud platform. This enables remote monitoring, where users can check live weather data on their mobile phones using the Blynk app.The system runs continuously and updates data at regular intervals. This real-time monitoring helps track environmental changes and supports better decision-making, especially in agriculture and environmental applications.</p>

## Features
- Real-time weather monitoring
- Wireless data transmission
- Mobile app visualization
- Low-cost and energy efficient<br>
## Applications
- Agriculture
- Environmental Monitoring
- Smart Homes
- Disaster Management<br>
## Advantages
- Low cost
- Easy to use<br>
## Limitations
- Depends on internet
- Limited sensor accuracy<br>
## Future Scope
- Add AI-based weather prediction
- Solar-powered system
- SMS alerts for farmers<br>
# Conclusion<br>
<p align="justify">
The Weather Monitoring System using ESP32 and Blynk IoT is an efficient and reliable solution for real-time environmental monitoring. It provides accurate data and remote accessibility, making it highly useful in agriculture and smart systems. This project demonstrates how IoT can be used to create smart and connected solutions for real-world problems.</p>
