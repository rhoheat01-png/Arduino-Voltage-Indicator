# Arduino Voltage Indicator

An Arduino-based voltage level indicator that uses a potentiometer as an analog input and three LEDs to indicate different voltage levels.

## Overview

This project demonstrates analog input reading and threshold-based decision making using an Arduino Uno.

The potentiometer provides a variable analog voltage to the Arduino's analog input. Based on the measured value, one of three LEDs is turned on to indicate the corresponding voltage level.

## Features

- Reads analog input using the Arduino Uno ADC
- Uses a potentiometer to provide a variable input
- Indicates voltage level using three LEDs
- Demonstrates analog-to-digital conversion
- Demonstrates conditional logic for threshold detection

## Components

- Arduino Uno
- Potentiometer
- 3 × LEDs
- Resistors
- Jumper wires
- Breadboard

## How It Works

The potentiometer produces an analog voltage that is read by the Arduino through an analog input pin.

The Arduino converts the analog signal into a digital value. The program compares this value with predefined thresholds and activates the corresponding LED.

The three LEDs represent:

- Low voltage level
- Medium voltage level
- High voltage level

## Technologies

- Arduino Uno
- C/C++
- Analog Input
- Digital Output
- ADC
- Arduino IDE

## Project Structure

```text
Arduino-Voltage-Indicator/
│
├── Voltage-Indicator-Arduino/
│   └── Voltage-Indicator-Arduino.ino
│
└── README.md
