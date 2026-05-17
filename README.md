# **STM32 CubeSat**
A Cube Satelitte Personal Project built on STM32F446RE
## Summary
This project serves as a hands-on introductory experience to embedded software engineering. The concept entails having the STM32F446RE microcontroller interact with different sensors that would be used in real-world satellite. The microcontroller will be communicating with multiple peripherals using different communication protocols to store telemtry data into a microSD card.
## Motivation and Goals
My academic and professional experience has been purely software oriented. I have worked professionally as a Software Engineer in a Lab Software environment and I would like to make the transition to space embedded software.

My goal for this project is to learn and use common communiction protocols that would be found in flight ready avionics to help bridge the gap between my past experience and future oppportunities.
## Hardware
Hardware used on this project include:
- **STM32 NUCLEO-F446RE**

    <img src=img/stm32_nucleo.jpg height=150 width=auto></img>
- **BMP280 Barometer/Temperature Sensor**

    <img src=img/bmp280.jpg height=150 width=auto></img>

- **MPU-6050 IMU (Inertial Measure Unit)**

    <img src=img/mpu6050.jpg height=150 width=auto></img>
- **QMC5883L Magnetometer**

    <img src=img/qmc5583p.jpg height=150 width=auto></img>
- **NEO-6M GPS Module**

    <img src=img/neo6mv2.jpg height=150 width=auto></img>
- **MicroSD Card Module**

    <img src=img/microSD.jpg height=150 width=auto></img>
- **Breadboard + Jumper Wires**

    <img src=img/breadboard.jpg height=150 width=auto></img>

## Key Concepts
Key Concepts Explored in this project:
- **Bare metal programming**
- **I<sup>2</sup>C**

    <img src=img/i2c.jpg ></img>
    - **Inter-Integrated Circuit Protocol** is a two wire serial communication protocol that using a *serial data line* (SDL) and a *serial clock line* (SCL). The communication bus can have multiple devices sending and receiving data.

    - Each device in the bus has a unique address that sends or receives the appropriate data.
        - Devices come builtin with their own address such as the **BMP280** which has an address of *0x58*.
- **SPI**
- **UART**
- **FreeRTOS**
- **Sensor Fusion**

## Architecture and Design
TBD
## Future Plans and Enhancements
TBD