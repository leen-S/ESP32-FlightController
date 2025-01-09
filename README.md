# ESP32 Flight Controller

## Overview

This repository contains all the necessary files for the **ESP32 Flight Controller** project. Designed for educational and practical purposes, this project showcases how an ESP32 microcontroller can be used to develop a flight controller. It includes firmware, schematics, PCB designs, and manufacturing files to bring the project to life.

![image alt](https://github.com/leen-S/ESP32-FlightController/blob/3d8469d0caf29110d258e8f79a5221c18e0c0ba8/PCBLayout.jpg)
---

## Repository Structure

### 1. **ESP32-Flight-Controller--main**
This folder contains:
- **Code**: The firmware written for the ESP32 microcontroller to manage and control the drone's operations.
- **Schematics**: Circuit diagrams detailing the hardware connections and design.

### 2. **PCB Designs/KiCAD**
This folder contains:
- **Sketches**: Conceptual sketches of the PCB layout.
- **PCB Layout**: The complete PCB design created using KiCAD.
- **Manufacturing and Gerber Files**: Files required for manufacturing the PCB, including drill files, silkscreen layers, and solder masks.

---

## How to Use

### 1. **Setup and Prerequisites**
- Install the necessary tools:
  - Arduino IDE (or PlatformIO) for uploading the firmware.
  - KiCAD for viewing and editing PCB designs.
- Ensure you have an ESP32 Dev Kit and other necessary components as specified in the schematics.

### 2. **Firmware Installation**
- Navigate to the `ESP32-Flight-Controller--main` folder.
- Open the provided `.ino` or equivalent firmware file in your IDE.
- Configure the project-specific parameters (e.g., pin mappings and calibration values).
- Upload the firmware to the ESP32 using a USB connection.

### 3. **PCB Manufacturing**
- Navigate to the `PCB Designs/KiCAD` folder.
- Use the Gerber files to manufacture the PCB:
  - Upload them to a PCB manufacturer (e.g., JLCPCB, PCBWay).
- Assemble the components as per the provided schematics.

---

## Features
- **ESP32-based Control**: Utilizes the ESP32 microcontroller for real-time flight control.
- **Modular Design**: The project is organized into distinct files for ease of use and modification.
- **Custom PCB**: Designed using KiCAD for a compact and efficient layout.
- **Open Source**: Fully customizable and adaptable for different applications.

---

## Acknowledgment
Special thanks to **@pratikphadte** for making amazing videos.

---

## Contributing
Contributions are welcome! Feel free to:
- Submit bug reports or feature requests via the Issues tab.
- Fork the repository and submit pull requests with improvements.

---

## License
This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the code and designs with proper attribution.

---

## Contact
For questions or collaboration, reach out via:
- **Email**: neelalohitk@gmail.com
- **LinkedIn**: https://www.linkedin.com/in/neelalohit-korlhalli/

---

Happy Building! 🚀
