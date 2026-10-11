# ESP32-IoT-Monitoring-System
# ESP32 IoT Monitoring System

 Overview
An ESP32-based IoT project that monitors environmental conditions and acceleration, detects abnormal events, displays sensor readings on an OLED screen, and reports data to ThingSpeak.

 Features
- Temperature and humidity monitoring using DHT11
- Acceleration monitoring using ADXL345
- Vibration detection using a vibration sensor
- OLED display using SH1106 128×64
- Buzzer alerts for abnormal conditions
- ThingSpeak cloud data reporting over Wi-Fi

 Hardware Requirements
- ESP32 development board
- DHT11 temperature and humidity sensor
- ADXL345 accelerometer
- SH1106 128×64 OLED display
- Vibration sensor module
- Buzzer
- Jumper wires and a suitable power supply

 Software and Libraries
- Arduino IDE
- ESP32 Arduino Core
- U8g2
- Adafruit Unified Sensor
- Adafruit ADXL345
- DHT sensor library
- Wi-Fi and HTTPClient libraries

How It Works
The ESP32 reads temperature, humidity, and acceleration data. It checks for abnormal acceleration, high temperature, and vibration events. Sensor readings and event status are displayed on the OLED, and monitoring data is sent to ThingSpeak when Wi-Fi is available.

 Setup
1. Install the ESP32 board package in Arduino IDE.
2. Install the required sensor and OLED libraries.
3. Connect the sensors according to your circuit diagram.
4. Configure Wi-Fi credentials and ThingSpeak settings locally.
5. Select your ESP32 board and port.
6. Compile and upload the sketch.
7. Verify sensor readings, alerts, and cloud reporting.
 Project Status
Prototype — testing and validation required.
