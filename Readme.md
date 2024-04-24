# FreeRTOS Finite State Machine for Sensor Polling and Decision Making

## Overview
This project implements a Finite State Machine (FSM) using FreeRTOS for sensor polling and critical decision making. The system receives interrupts from sensors, processes the data using a state machine, and transfers the interpreted results through SPI to a Microprocessor Unit (MPU) running Linux for further processing.

## Features
- Utilizes FreeRTOS for task scheduling and management.
- Implements a Finite State Machine (FSM) for efficient sensor data processing.
- Handles interrupts from sensors in real-time.
- Communicates with an MPU via SPI for data transfer and further processing.

## Directory Structure
- **FreeRTOS/**: Contains the FreeRTOS source files.
- **Drivers/**: Device drivers for sensors or any other peripherals.
- **Inc/**: Header files for the project.
- **Src/**: Source files for the application logic.
- **startup/**: Startup files for the microcontroller.
- **README.md**: Project documentation.


## Dependencies
- FreeRTOS: Real-time operating system for microcontrollers.
- Device drivers: Drivers for sensors and any other peripherals used in the project.

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).
