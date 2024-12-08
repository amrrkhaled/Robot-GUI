# Robot Simulator: Advanced GUI for Robotics Control and Simulation

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Acknowledgements](#acknowledgements)

---

## Overview
The **Robot Simulator** is a comprehensive Python-based GUI application for controlling and simulating a robotic system. Designed with a professional approach, it integrates real-time video streaming, QR code scanning, wireless communication, and joystick inputs to offer a versatile solution for robotics projects.

---

## Features
1. **Modern GUI Design**
   - Developed with PyQt5 for an interactive and responsive user interface.
   - Dynamic components like sliders, buttons, and labels for intuitive interaction.

2. **Camera and QR Code Integration**
   - Real-time video feed from a webcam using OpenCV.
   - Dynamic QR code scanning to extract and display data on the GUI.

3. **Motion and Gripper Control**
   - Full control over the robot’s movement and gripper using buttons and keyboard inputs.
   - Joystick support for enhanced user experience.

4. **Wireless Communication**
   - Communicates with the robot via WiFi, ensuring smooth and reliable data transfer.
   - Sends and receives coordinates and commands in real-time.

5. **Joystick Integration**
   - Supports PS4 joystick input for controlling the robot.
   - Configurable button mapping through JSON configuration.

6. **Adjustable Speed Control**
   - Slider to dynamically adjust the robot's movement speed.

---

## Technologies Used
- **Python**: Core programming language.
- **PyQt5**: GUI framework.
- **OpenCV**: For video capture and QR code scanning.
- **pygame**: Joystick integration.
- **JSON**: Configuration for joystick button mappings.

---

## Installation

### Prerequisites
- Python 3.8+
- Required Python packages (installed via `pip`):
  ```bash
  pip install pyqt5 opencv-python pyzbar pygame



