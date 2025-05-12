# ESP32 Weather Station with Web Monitoring
> An IoT environmental monitoring system powered by ESP32 microcontroller

## Overview
This project implements a comprehensive weather monitoring solution that combines hardware sensors with real-time web visualization. The system captures temperature, humidity, and atmospheric pressure data through connected sensors and transmits it to a web interface for continuous monitoring.

### Features
* **Multi-sensor integration**: DHT22 (digital) and LM35 (analog) temperature sensors
* **MQTT Communication**: Efficient data transmission protocol
* **Real-time visualization**: Dynamic charts and gauges
* **Alert system**: Configurable thresholds with notification capability
* **Data logging**: Historical tracking with CSV export

## Hardware Components
- ESP32 microcontroller
- DHT22 temperature and humidity sensor
- LCD 16x2 I2C display
- 5V DC Fan with TIP122 transistor control
- WiFi connectivity module

> **Note**: Complete hardware setup instructions available in the documentation folder

### System Architecture
The project follows a three-layer architecture:
1. **Sensing Layer**: ESP32 with connected sensors
2. **Communication Layer**: MQTT protocol over WiFi
3. **Application Layer**: Web dashboard for visualization

## Video Tutorials and Demonstrations
For full video tutorials on building and configuring this system, visit:
[Environmental IoT Solutions](https://www.youtube.com/playlist?list=PLrZbkNpNVSwwNmVhX9jaTQYm4oCd6WHbP)
