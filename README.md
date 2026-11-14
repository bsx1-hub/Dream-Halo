# Dream-Halo  
### Gesture-Controlled Circadian Ambient Light

Dream Halo is an STM32-based ambient lighting system.

The project combines touchless gesture control, programmable RGB lighting, and real-time scheduling to create an interactive wall-mounted LED lamp with an eclipse-inspired design.

## Features
- **Gesture Control:** Adjust LED brightness using hand movements detected by a Time-of-Flight sensor.
- **Dream Mode:** Smooth purple, lavender, and blue lighting animations.
- **Sunrise Simulation:** Gradually transitions from warm colors to brighter lighting over 30 minutes.
- **RTC Scheduling:** Automatically initiates sunrise lighting at a programmed time.
- **Brightness Memory:** Maintains the last selected brightness after the user's hand is removed.

## Hardware
- STM32 Nucleo Microcontroller
- VL53L1X Time-of-Flight Sensor
- DS3231 Real-Time Clock Module
- WS2812B Addressable RGB LED Strip
- 5V Power Supply and Logic Level Shifter
- Custom 3D-Printed Enclosure and Diffuser

## Software
- C / Embedded C
- STM32CubeIDE
- STM32 HAL Libraries
- I²C Communication
- Timer/DMA-Based LED Control (planned)

## Project Goals
Develop a functional prototype demonstrating embedded sensor integration, nonblocking firmware, addressable LED control, and time-based lighting automation.
