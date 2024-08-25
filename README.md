# Final Project - Joseph Dengler

## Project Overview

This repository showcases the **Smart Thermostat** project I developed as part of my coursework for CS-350: Emerging Systems Architectures and Technologies. The project's primary goal was to design and implement a smart thermostat using the TI CC3220x LAUNCHXL board. The thermostat prototype is capable of reading room temperature, controlling a simulated heater (represented by an LED), adjusting the temperature setpoint, and simulating data transmission to a server via UART.

## Problem Statement

The project addresses the challenge of managing and controlling room temperature efficiently using a smart thermostat. The thermostat reads temperature data from a sensor, compares it to a user-defined setpoint, and controls a heater accordingly. Additionally, it sends status updates, including temperature, heater state, and elapsed time, to a server using UART communication.

## Key Features

- **Temperature Reading:** The thermostat reads room temperature using an I2C temperature sensor.
- **Heater Control:** Based on the temperature reading and setpoint, the thermostat controls an LED, simulating a heater's on/off state.
- **Setpoint Adjustment:** Users can adjust the temperature setpoint using buttons on the board.
- **Data Transmission:** The system transmits data to a server via UART, including the temperature, setpoint, heater state, and elapsed time.
- **Task Scheduling:** The project implements a task scheduler to manage temperature readings, button inputs, and data transmissions at specific intervals.

## What I Did Well

I successfully implemented a robust and efficient task scheduler that handles multiple operations with precise timing. The design and implementation of the hardware and software components were well-coordinated, ensuring smooth operation and real-time response to user inputs and temperature changes.

## Areas for Improvement

While the project met the requirements, there is room for improvement in optimizing the code for better readability and maintainability. Additionally, future iterations could explore more sophisticated control algorithms for better temperature regulation and integrating cloud-based data storage for enhanced functionality.

## Tools and Resources

- **TI CC3220x LAUNCHXL Board:** Used for developing the thermostat prototype.
- **I2C and UART Protocols:** Employed for sensor communication and data transmission.
- **GitHub:** Used for version control and project collaboration.

## Transferable Skills

The skills gained from this project, such as task scheduling, hardware-software integration, and real-time system design, are highly transferable to other embedded systems projects and coursework. The experience of working with UART and I2C communication protocols will also be valuable in future endeavors.

## Making the Project Maintainable, Readable, and Adaptable

I ensured that the codebase is well-commented, with clear variable and function names to enhance readability. The modular design of the code allows for easy updates and modifications, making the project adaptable for future enhancements, such as integrating cloud connectivity or expanding the control algorithms.

## Artifacts

The following artifacts best showcase my work in this project:

1. **Task Scheduler Flowchart:** Visualizes the operation of the task scheduler in the smart thermostat project.
<div align="center">   
  <img src="https://github.com/user-attachments/assets/503014de-9c9e-4466-831a-820e8049d94c" alt="Flowchart">
</div>

3. **[Smart Thermostat Report](Smart%20Thermostat%20Report%20-%20Joseph%20Dengler.docx):** Provides a detailed explanation of the project's design, implementation, and hardware analysis.
