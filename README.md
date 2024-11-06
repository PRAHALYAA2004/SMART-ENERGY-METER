# SMART-ENERGY-METER

## Overview

This project involves designing a **Smart Energy Meter** using an STM32F401CCU6 microcontroller. The device monitors real-time power consumption by measuring current and voltage using connected sensors. The readings are processed and displayed on an LCD, providing a user-friendly way to track energy usage.

### Problem Statement
Create a system that:
- Measures current and voltage from an AC main supply.
- Computes and displays power consumption using an LCD.
- Integrates features like real-time tracking, data logging, and IoT compatibility for remote monitoring.

### Key Features
1. **Real-Time Power Measurement**: Continuously calculates power consumption based on voltage and current readings.
2. **Energy Usage Calculation**: Tracks cumulative energy consumption over time, displayed in watt-hours or kilowatt-hours.
3. **Precision Sensing**: Utilizes voltage and current sensors (ZMPT101B, ACS712) for high accuracy.
4. **LCD Display**: Shows real-time data, including voltage, current, and power consumption.
5. **Automated Power Calculations**: Processes data to compute instantaneous power using (P = V * I).

### Applications
- Household or industrial energy tracking for optimized power usage.
- Automated alerts for high consumption.
- Data logging for analyzing power trends.
- Remote monitoring via IoT integration for smart home systems.

## Hardware Components
- **STM32F401CCU6 Microcontroller Board**
- **Current Sensor (ACS712 - Hall Effect)**: Measures current flowing through the AC line.
- **Voltage Sensor (ZMPT101B)**: Detects AC voltage levels.
- **LCD Display (16*2 - Parallel)**: Displays real-time values of AC voltage.
- **Energy Meter IC**: Ensures accurate energy measurements.
- **LED**: For visual power alerts.
- **ST-Link**: For programming and debugging.
- **Breadboard and Connecting Wires**: For circuit setup and prototyping.

## Software Requirements
- **STM32CubeIDE**: Development environment for STM32.

## Circuit Design
![image](https://github.com/user-attachments/assets/6f486b21-7e8e-4f76-941b-b099bc39686f)

## Setup and Usage
1. **Connect Sensors**: Attach voltage and current sensors to the STM32 ADC channels.
2. **Configure LCD**: Set up the LCD to display voltage, current, and power.
3. **Load Code**: Program the STM32 using STM32CubeIDE.
4. **Run and Monitor**: Observe real-time readings on the LCD, with warnings for overload conditions via LED alerts.

## Results
- **Without Main Supply**:
  - Current (I): 0.00 A
  - Voltage (V): 0.00 V
- **With Main Supply**:
  - Current (I): 0.71 A
  - Voltage (V): 219.41 V

## Future Enhancements
- Integration with IoT platforms for remote access.
- More advanced data logging and historical analysis.
- Mobile application interface for user-friendly monitoring.


**Project by**

CB.EN.U4CSE22430 PRIYADARSHINI RAJESH

CB.EN.U4CSE22432 PRAHALYAA A

CB.EN.U4CSE22431 TRISHIKA REDDY

CB.EN.U4CSE22441 INDIRA SATYA SAI

**19CSE303 Embedded Systems**

**Department of Computer Science and Engineering**

**Amrita School of Computing**

**Amrita Vishwa Vidyapeetham, Coimbatore, India**




## License
This project is open-source and available for use under the MIT License. 



---------------------------------------------------------------------------------------------------------------------------------------------
