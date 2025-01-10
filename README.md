# RoboMop: Arduino-Based Smart Vacuum Cleaner Robot

RoboMop is an autonomous smart vacuum cleaner robot designed to navigate and clean floors efficiently. Built using readily available components and an Arduino microcontroller, it offers a cost-effective solution for automated floor cleaning.

## Features

- **Autonomous Navigation**: Utilizes ultrasonic sensors for obstacle detection and avoidance.
- **Efficient Cleaning**: Equipped with a suction mechanism to collect dust and debris.
- **Compact Design**: Constructed using lightweight materials for easy maneuverability.

## Materials Required

- **Microcontroller**: Arduino Uno
- **Motor Shield**: Arduino Motor Shield
- **Motors**:
  - 4x DC Gear Motors with Wheels
  - 1x Servo Motor
- **Sensors**:
  - 1x Ultrasonic Sensor (HC-SR04)
- **Power Supply**:
  - 12V AC to DC Adapter
- **Additional Components**:
  - Plastic Bottle (for the body)
  - Plastic Lid (for the base)
  - Connecting Wires
  - Suction Fan (for vacuum mechanism)
  - Screws and Mounting Hardware

## Assembly Procedure

1. **Chassis Construction**:
   - Cut the plastic bottle to create the main body of the robot.
   - Attach the plastic lid to serve as the base.

2. **Motor Installation**:
   - Mount the DC gear motors with wheels to the base for movement.
   - Attach the servo motor to the front for sensor rotation.

3. **Sensor Placement**:
   - Fix the ultrasonic sensor onto the servo motor to allow rotational scanning for obstacles.

4. **Suction Mechanism**:
   - Install the suction fan inside the body to create the vacuum effect.
   - Ensure proper airflow by creating inlet and outlet vents.

5. **Electronics Integration**:
   - Connect the Arduino Uno and Motor Shield to control the motors and process sensor data.
   - Wire the ultrasonic sensor and servo motor to the Arduino for obstacle detection and navigation.

6. **Power Supply**:
   - Connect the 12V power supply to the Arduino and motors.
   - Ensure all connections are secure to prevent short circuits.

7. **Programming**:
   - Upload the provided Arduino code to the microcontroller to enable autonomous operation.

## Code

The Arduino code for RoboMop is available in the `robomop.ino` file in this repository. It controls the robot's movement, obstacle detection, and cleaning routines.

## Usage

1. **Power On**: Connect the power supply to activate the robot.
2. **Autonomous Cleaning**: RoboMop will begin navigating and cleaning the floor automatically.
3. **Obstacle Avoidance**: The ultrasonic sensor detects obstacles, and the robot adjusts its path accordingly.
4. **Manual Override**: If needed, you can manually control the robot by modifying the code for specific behaviors.

## Circuit Diagram



![cleaned_circuit_diagram](https://github.com/user-attachments/assets/461a43d6-bf32-4095-ba16-9c12608a278e)
