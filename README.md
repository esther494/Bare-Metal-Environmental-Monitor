# PlantGuard: Bare-Metal Environmental Monitor
**Bare-metal programming, RTOS, sensors, UART, I2C, and ADC**

## Project Overview
Growing crops can be challenging, especially when building a greenhouse for plants and crops that require specific temperature and humidity conditions. This project helps those who want to build their own plant monitoring system, enabling users to wirelessly monitor their greenhouse environment.

Before diving into the technical details, let’s define a greenhouse. A greenhouse is a structure that regulates temperature and humidity by trapping solar radiation through transparent materials and preventing heat from escaping easily. Key factors to consider in a greenhouse include ventilation, heating, cooling, lighting, and CO2 levels.

Managing all of this can be overwhelming for newcomers, so this project allows users to monitor the greenhouse environment from anywhere, providing real-time data on temperature, humidity, light, and moisture levels.

As the name suggests, this project primarily uses bare-metal programming to ensure reliability and reduce overhead. By customizing the code down to the bare metal of the system, the project runs faster and uses resources more efficiently.

## Objectives
The specific functions of this project include:
- Collecting sensor data in the greenhouse (temperature, humidity, light, and moisture levels)
- Sending this data to your PC or Raspberry Pi for display
- Allowing the user to track and monitor the greenhouse environment, as well as the comprehensive weather data of the area

## Hardware Requirements
- [STM32F401RE](https://www.st.com/en/microcontrollers-microprocessors/stm32f401re.html)
- [ESP32-DevKitC](https://www.espressif.com/en/products/devkits/esp32-devkitc)
- [Raspberry Pi 3 Model B+](https://www.raspberrypi.com/products/raspberry-pi-3-model-b-plus/)
- [AM2320 Digital Temperature and Humidity Sensor](https://www.adafruit.com/product/3721)
- [DFR0026 Analog Ambient Light Sensor](https://www.dfrobot.com/product-1004.html)
- [Gravity: Analog Soil Moisture Sensor for Arduino](https://www.dfrobot.com/product-599.html)
