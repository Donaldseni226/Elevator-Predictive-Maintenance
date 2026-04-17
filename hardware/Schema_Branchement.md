# Wiring Diagram and Connection Instructions for Sensors to ESP32

## Overview
This document provides detailed information on how to connect various sensors to an ESP32 microcontroller. The ESP32 offers multiple GPIO (General Purpose Input/Output) pins, allowing for various sensor integrations.

## Required Components
1. ESP32 Development Board
2. Ultrasonic Sensor (HC-SR04)
3. PIR Motion Sensor
4. Temperature and Humidity Sensor (DHT11 or DHT22)
5. Connection Wires
6. Breadboard (optional)

## Wiring Diagram
![Wiring Diagram](https://dummyimage.com/600x400/000/fff&text=Wiring+Diagram+Placeholder)

### Sensor Connections
- **Ultrasonic Sensor (HC-SR04)**
   - VCC to 5V
   - GND to GND
   - Trig to GPIO 12
   - Echo to GPIO 13

- **PIR Motion Sensor**
   - VCC to 5V
   - GND to GND
   - Signal to GPIO 14

- **DHT Sensor (DHT11/DHT22)**
   - VCC to 3.3V
   - GND to GND
   - Data to GPIO 15

## Connection Instructions
1. **Prepare the ESP32**: Make sure you have the latest ESP32 board package installed in your Arduino IDE.
2. **Connect the Sensors**: Use the wiring information provided above to connect each sensor to the corresponding GPIO pins on the ESP32.
3. **Upload the Code**: Implement the code to read and process the sensor data. Ensure that you have included the necessary libraries for each sensor.
4. **Test the Setup**: After uploading the code, monitor the Serial Output to see the sensor readings and confirm that everything is functioning correctly.

## Troubleshooting
- If the sensors do not work as expected, double-check the wiring and ensure that all connections are secure.
- Make sure that the correct GPIO pins are defined in your code.

## Conclusion
Following these instructions will help you successfully set up various sensors with your ESP32 for your project. For further questions or details, please refer to the individual sensor datasheets and documentation.

---

*Date Created: 2026-04-17 05:54:31 UTC* 
*Maintainer: Donaldseni226*