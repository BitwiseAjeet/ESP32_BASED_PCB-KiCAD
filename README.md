# ESP32_BASED_PCB-KiCAD
This project involved the end-to-end design and development of a compact, low-power IoT system using the ESP32-C3-02 SoC and integrated TP4056 Li-ion battery charger. The goal was to create a reliable and modular platform for wireless environmental data monitoring, powered by a rechargeable battery with onboard protection and USB-C support.
Key Features
Microcontroller: ESP32-C3-02 SoC for Wi-Fi and BLE connectivity.
Power Management: TP4056 IC for single-cell Li-ion battery charging with thermal regulation.
Battery Protection: Integrated under-voltage lockout and trickle charging.
Sensors and Modules:
BME280 for temperature, humidity, and pressure sensing.
Ambient light and sound sensors.
Mini SD card reader for data storage.
Flash memory for additional storage.
Display: I2C OLED for real-time data visualization.
Power Inputs:
USB-C connector for charging and data transfer.
LiPo battery connector with onboard charging circuitry.
Indicators: LED indicators for charge status (charging and full).
Design Highlights
Power Supply Integration:

USB-C provides power for both charging and system operation.
TP4056 handles battery charging and protection.
Power supplied to the ESP32-C3-02 is regulated for stability.
Modular Architecture:

Supports various sensors and peripherals for IoT applications.
Expandable via additional I2C devices.
Safe and Efficient Charging:

Programmable charging current using an external resistor.
Automatic charge termination and battery protection.
Compact and Reliable Layout:

Optimized PCB traces for minimal power loss.
Thermal management for the TP4056 and other components.
Applications
IoT edge devices for environmental monitoring.
Battery-powered data logging systems.
Prototyping platform for ESP32-based projects.
Repository Contents
Schematic and PCB Layout: KiCad files for the board design.
Firmware: Source code for the ESP32-C3-02 to interface with sensors and peripherals.
Documentation:
Datasheets for the TP4056 and other components.
Assembly instructions.
Testing procedures.
License: MIT License.
