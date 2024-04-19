# Ultrasonic Radar

Welcome to the Servo and Ultrasonic Sensor Radar project! This repository contains code and documentation for creating a radar system using a servo motor and ultrasonic sensor, as well as a graphical user interface (GUI) created with Processing software.

## Table of Contents

- [Features](#features)
- [Hardware](#hardware)
- [Software](#software)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Media](#media)
- [Contributing](#contributing)
- [Author](#author)

## Features

- **Servo Control**: Rotates a servo motor to sweep the ultrasonic sensor across a 180-degree angle.
- **Distance Measurement**: Uses the ultrasonic sensor to measure the distance of obstacles within the radar's range.
- **Real-Time Radar Display**: Visualizes the radar data on a GUI created with Processing software.
- **Object Detection**: Identifies objects within range and displays their distance and angle on the GUI.

## Hardware

- **Microcontroller**: Arduino-compatible board (e.g., Arduino Uno).
- **Ultrasonic Sensor**: HC-SR04 sensor for distance measurement.
- **Servo**: Standard servo motor for controlling the sensor's angle.
- **Other**: Jumper wires, breadboard, and power source.

## Software

- **Arduino IDE**: For uploading the provided Arduino sketch to the microcontroller.
- **Processing**: For running the Processing sketch to visualize radar data.
- **Libraries**: Arduino libraries (`Servo`) and Processing libraries (`processing.serial`).

## Getting Started

### Prerequisites

- Install the Arduino IDE and Processing software on your computer.
- Ensure that you have the necessary Arduino and Processing libraries installed.

### Installation

1. Clone this repository:

    ```bash
    git clone https://github.com/yourusername/servo-ultrasonic-radar.git
    cd servo-ultrasonic-radar
    ```

2. **Arduino Code**:
    - Open the `arduino_code.ino` file in the Arduino IDE.
    - Compile and upload the code to your Arduino board.
  
3. **Processing Sketch**:
    - Open the `processing_code.pde` file in Processing.
    - Modify the COM port in the sketch to match your Arduino board's port.
    - Run the Processing sketch.

## Usage

1. **Setup**:
    - Connect the hardware as described in the code comments.
    - Ensure your Arduino and Processing are properly set up.

2. **Operation**:
    - Once both the Arduino and Processing code are running, observe the real-time radar display in the Processing GUI.
    - The GUI will show the radar sweep, detected objects, and their corresponding distances and angles.
      
## Media
 
<p align="center">
    <img src="radarimg2.jpeg" height="400" width="300" alt="Error">
    <img src="radarimg3.jpeg" height="400" width="300" alt="Error">
</p>

## Contributing

Contributions are welcome! If you find any bugs, issues, or have suggestions for improvements, please open an issue or submit a pull request. Happy coding!

## Author

This project was created by Abhishek Rajput.
