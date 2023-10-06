# Automatic Washroom Light Control

This is a simple Arduino-based project for automatically controlling a washroom light based on the presence of people. The system turns on the light when someone enters the washroom and turns it off when there is no one inside.

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Hardware Setup](#hardware-setup)
- [Usage](#usage)
- [Customization](#customization)
- [License](#license)

## Features

- Automatic control of a washroom light.
- Sensors detect the entry and exit of people.
- Uses Arduino for microcontroller programming.
- Serial debugging for monitoring system behavior.

## Requirements

To replicate this project, you will need the following:

- Arduino board (e.g., Arduino Uno)
- Infrared or ultrasonic sensors (for detecting people)
- LED light (or any light source you want to control)
- Jumper wires
- Breadboard (optional, for prototyping)
- Arduino IDE for programming

## Hardware Setup

1. Connect the infrared or ultrasonic sensors to digital pins on your Arduino. In the provided code, pin 7 is used for entry detection (LOW when someone enters) and pin 8 for exit detection (LOW when someone exits). Adjust the connections according to your sensor specifications.

2. Connect the LED light (or your chosen light source) to a digital pin (e.g., pin 9) on the Arduino. This pin will control the light based on the presence of people.

3. Ensure proper power supply for your Arduino and sensors.

## Usage

1. Upload the provided Arduino sketch (the code you have) to your Arduino board using the Arduino IDE.

2. Open the Arduino Serial Monitor to monitor the system behavior. It will display messages indicating the number of people inside the washroom and their entry/exit status.

3. Test the system by entering and exiting the washroom. The light should automatically turn on when someone enters and turn off when there are no people inside.

## Customization

You can customize this project to fit your specific requirements:

- Adjust the pin numbers for sensors and the light source in the Arduino code if you have different hardware connections.
- Modify the delay duration (e.g., `delay(300)`) to control how quickly the system responds to changes in presence.
- Implement additional features or sensors as needed for your application.

## License

This project is open-source and available under the [MIT License](LICENSE). You are free to use, modify, and distribute it as per the terms of the license.
