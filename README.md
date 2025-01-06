

# Rover and Robotic Arm

This project involves the development of a rover equipped with a robotic arm, designed for tasks requiring mobility and manipulation.

## Repository Contents

- **SpaceTrekMachine_Robotic_arm documentation.pdf**: Comprehensive documentation detailing the design, assembly, and operation of the robotic arm.

- **Spacetrek_Armbot.apk**: Android application for controlling the robotic arm via Bluetooth.

- **robotic_arm_code.ino**: Arduino source code for operating the robotic arm.

- **six_dc.ioc**: Configuration file for the STM32 microcontroller, managing six DC motors.

## Getting Started

### Prerequisites

- **Hardware**:
  - Arduino Mega 2560
  - Bluetooth module HC-05
  - Motor driver (L298 Motor Driver Module)
  - Servo motors (2 for the robotic arm)
  - Power supply

- **Software**:
  - Arduino IDE
  - Android device for the control application

### Hardware Setup

1. **Motor Driver Connections**:
   - IN1 to Arduino pin 2
   - IN2 to Arduino pin 3
   - IN3 to Arduino pin 4
   - IN4 to Arduino pin 5

2. **Servo Motor Connections**:
   - Base motor to Arduino pin 6
   - Arm motor to Arduino pin 7

3. **Bluetooth Module Connections**:
   - RX to Arduino pin 10
   - TX to Arduino pin 11

Ensure all grounds are connected, and VCC is connected to the 5V supply.

### Software Setup

1. **Arduino Code**:
   - Open `robotic_arm_code.ino` in the Arduino IDE.
   - Upload the code to the Arduino Mega 2560.

2. **Android Application**:
   - Install `Spacetrek_Armbot.apk` on your Android device.
   - Pair the device with the HC-05 Bluetooth module.
   - Use the application to control the rover and robotic arm.

## Operation

- **Rover Movement**: Controlled via the Android application, allowing forward, backward, left, and right movements.

- **Robotic Arm Control**: The arm has two degrees of freedom, controlled through the application for tasks such as picking and placing objects.

## Documentation

For detailed information on the design, assembly, and operation, refer to the `SpaceTrekMachine_Robotic_arm documentation.pdf` included in this repository.

## Acknowledgments

This project is inspired by various open-source rover and robotic arm projects available in the community.



---

For any issues or contributions, please feel free to open an issue or submit a pull request. 
