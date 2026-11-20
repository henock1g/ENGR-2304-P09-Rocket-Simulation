# ENGR 2304 - P09 Rocket Launch Simulation

## Description
This project simulates a rocket launch system using an Arduino Uno in Tinkercad. The system increases compressor pressure to a specified target before initiating a rocket countdown.

## Features
- **Pressure Input:** Accepts binary (`10100`) or hexadecimal (`0x14`) values through Serial Monitor.
- **Compressor:** Automatically simulates pressure increasing to the target.
- **LCD:** Displays pressure readings and countdown.
- **LEDs:** Four LEDs display countdown numbers in binary.
- **Completion:** Displays "SIM COMPLETE" after countdown.

## Components
Arduino Uno, 16x2 I2C LCD, four LEDs, potentiometers, breadboard, and connecting wires.

## How to Run
1. Open the Tinkercad circuit and start the simulation.
2. Open Serial Monitor and enter a binary or hexadecimal pressure value.
3. Click Send and wait for the pressure to reach its target.
4. Watch the countdown from 10 to 0.

## Input Examples
- `10100` = 20 PSI (binary)
- `0x14` = 20 PSI (hexadecimal)
- `1010` = 10 PSI (binary)

## Limitations
Compressor pressure is simulated automatically rather than measured using the second potentiometer.
