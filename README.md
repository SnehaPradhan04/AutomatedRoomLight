# Automated Light Control

This project is based on Arduino Uno and IR sensors. This is a simple project that can automatically control a room's lights based on a person's presence on the room. 
The system turns on the light when someone enters the room and turns it off when there is no one present.

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Hardware Setup](#hardware-setup)
- [Usage](#usage)

## Features

- Automatic control of a room's light.
- IR sensors can detect the entry and exit of people.
- Arduino Uno is used for microcontroller programming.

## Requirements

To make this project, we used the following:
- IR sensors(for the obstacle/person detection)
- Relay(to switch on and off the light source)
- Arduino Uno board(hardware) and Arduino IDE(software)
- Jumper wires for connection
- A light source(that is to be controlled)
- Power source(for Arduino Uno board and light source)
- Breadboard for making the circuit
  
## Hardware Setup

1. Connect the infrared sensors to digital pins on the Arduino Uno board. In the code, pin 7 is used for entry detection (LOW when someone enters) and pin 8 for exit detection (LOW when someone exits).

2. Connect the light source to a digital pin (in the code we used pin 9) on the Arduino. This pin will control the light based on the presence of people as it will be the output pin.

3. Ensure proper power supply to the Arduino, sensors and light source.


## Usage of the project

This project was made with aim to save electricity and electricity charges by turning off the the room's lights if mistakenly left on.


