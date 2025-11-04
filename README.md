# Smart_Glasses
This project consists of a custom-designed printed circuit board (PCB) intended for a prototype of smart glasses. The goal of the system is to track the wearer’s head movements using a 9-axis inertial measurement unit (IMU) and transmit the data wirelessly via Bluetooth.

All schematic design, PCB layout, component selection, and hardware integration were carried out by me using EasyEDA.

# Objectives

- Capture real-time head orientation and motion data

- Perform sensor fusion on-board to improve accuracy and stability

- Stream processed data wirelessly to an external device

- Power the system from a lightweight Li-ion/Li-poly battery suitable for wearable use

# Core Features
## ESP32-S3 Microcontroller
- Integrated Bluetooth Low Energy (BLE)
- On-board antenna
- Handles data acquisition and wireless transmission
- Programmable via USB thanks to the UART bridge

## BNO086 9-Axis IMU
- Accelerometer, gyroscope, and magnetometer
- Built-in ARM Cortex core enabling onboard sensor-fusion algorithms
- Outputs stable orientation and head-tracking data
- Battery Management System

# Supports single-cell Li-ion / Li-poly batteries
- Status LEDs indicating charging, full charge, and power conditions
- Over-charge and under-voltage protection

# USB-to-UART Programming Interface
- Enables quick firmware upload through standard USB
- Simplifies development and debugging

# Audio Output Stage
- Integrated low-power speaker amplifier
- Allows simple audio feedback or notifications
