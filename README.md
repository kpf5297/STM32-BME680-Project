# STM32-BME680-Project

## Project Overview
This project demonstrates how to interface a Bosch BME680 environmental sensor with an ST Discovery Development Board. The project involves reading temperature, humidity, pressure, and gas data from the BME680 sensor and displaying it on the built-in display of the development board.

## Components
- **ST Discovery Development Board**
- **Bosch BME680 Sensor**
- **Built-in Display**

## Features
- Initialize and read data from the BME680 sensor
- Display real-time sensor data on the built-in display
- Demonstrates I2C communication with the sensor

## Prerequisites
- **STM32CubeIDE**: Integrated Development Environment for STM32 microcontrollers
- **BME680 Sensor Library**: Available from Bosch or other trusted sources

## Getting Started

### 1. Setting Up the Hardware
Connect the BME680 sensor to the ST Discovery Development Board using the I2C interface:
- **SDA** -> I2C SDA pin on the board
- **SCL** -> I2C SCL pin on the board
- **VCC** -> 3.3V or 5V power supply
- **GND** -> Ground

### 2. Setting Up the Software
1. **Clone the Repository**
   ```sh
   git clone https://github.com/kpf5297/STM32-BME680-Project.git
   cd STM32-BME680-Project

### Running the Project
#### Build and Flash the Project
1. **Compile the project in STM32CubeIDE.**
2. **Flash the firmware onto the ST Discovery Development Board.**

#### Observe the Output
- **The built-in display should show real-time data from the BME680 sensor, including temperature, humidity, pressure, and gas levels.**

### Acknowledgements
- **Bosch for the BME680 sensor library and documentation.**
- **STMicroelectronics for the STM32 development ecosystem and tools.**
