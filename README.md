<h1>Smart Hat for Visually Challenged Person</h1>

<p>This project aims to develop a smart assistive hat designed to aid visually challenged individuals in navigating their surroundings with more independence. The system utilizes a Raspberry Pi, a camera, and an earphone to detect obstacles and provide real-time audio feedback to the user.</p>

## Key components
- Raspberry Pi: Serves as the core processing unit, handling the data from the camera and managing obstacle detection algorithms.
- Camera: Captures live video of the user's surroundings and helps in detecting objects and potential obstacles.
- Earphone: Provides audio alerts and guidance based on the processed data from the Raspberry Pi, offering real-time information to the user.

## Objectives
- To Develop a system to alert the user about nearby obstacles. Implement a face recognition system to identify individuals and inform the visually challenged user.
- To Design smart hat equipped with Raspberry pi and connectivity to detect obstacles, recognize objects, and provide real-time feedback to the user.
- To Conduct extensive testing and user feedback sessions to iterate and refine the design, ensuring that the final product meets the needs and preferences of visually challenged users. 


## Features
- Camera for Object Recognition.
- Speech Recognition and Voice Commands.
- Environment Awareness.
- Low Power Consumption.
- Compact and Wearable Design.
- Customizable Features.

## Design:-
<p>
  <img src="Images/design.png"/> 
</p>

## Components Used
- ESP32 microcontroller
- DHT11 temperature and humidity sensor
- MQ2 gas sensor
- SSD1306 OLED display
- Adafruit SSD1306 and DHT libraries
- WiFi library for ESP32
- ThingSpeak for data logging

## Software Requirement:
- [Arduino IDE](https://www.arduino.cc/)
> Arduino IDE used to upload programming in ESP32 Board with required library.
- [Thingspeak](https://thingspeak.com/)
> ThingSpeak is a cloud-based IoT analytics platform service that lets you collect, view, and examine real-time data streams. Data can be sent from your devices to ThingSpeak, enabling instantaneous live data display.

## Setup Instructions
1. **Hardware Setup:**
   - Connect DHT11 to GPIO 14 and MQ2 analog output to GPIO 34.
   - Wire SSD1306 OLED display to ESP32.

2. **Software Setup:**
   - Install required libraries listed in the `#include` section of [main.cpp](air_pollution_monitoring_esp32.ino).
   - Configure WiFi credentials in `setup()` function.

3. **ThingSpeak Configuration:**
   - Create a ThingSpeak account and channel.
   - Replace `apiKey` and `myChannelNumber` in [main.cpp](air_pollution_monitoring_esp32.ino) with your specific values.

## Usage
- Power on the device and monitor OLED display for real-time data.
- Data is automatically uploaded to ThingSpeak every 5 seconds.

## Result:
<p>The goal of the project at hand is to create an ESP32-based air pollution monitoring system for particular locations, such cafes, hotels, or industries. The system will use sensors to measure pollutants in real-time, such as nitrogen dioxide (NO2), carbon monoxide (CO), and particulate matter (p.m.2.5, PM10). The cloud-based IoT platform ThingSpeak will receive the data transmission for storage and analysis. The initiative does not include any control mechanisms; it only monitors and analyzes air quality. The system's objective is to enhance awareness and enable well-informed decision-making for indoor air quality management in specific public and private areas by offering extensive pollutant statistics.</p>
<p>
  <img src="Images/ThingSpeak op1.png"/> 
  <img src="Images/ThingSpeak op2.png"/> 
  <img src="Images/ThingSpeak op3.png"/> 
</p>

## Under the Guidence:
- [Prof.PRAKASHA G](https://www.linkedin.com/in/prakasha-g-76a609193)

## Authors:
- [SANDEEPKUMAR S](https://www.linkedin.com/in/sandeepkumar-s-233721241/)
- [MANOHAR P HIREMATH](https://www.youtube.com/@ManoharHiremath)
- [DARSHAN D](https://www.youtube.com/@Darshan_d_Naik)
- [RAGHAVENDRA M](https://www.instagram.com/_raghu_m_.46?igsh=MXNjNGcydG1vaWhiOQ==)
