
# ENGR 2304 - P09 Rocket Launch Simulation

## Description
This project simulates a rocket launch using an Arduino Uno in Tinkercad. The system increases compressor pressure until the target is reached, then begins a countdown.

## Features
- **Pressure:** Set target pressure (0–100 PSI) using the A0 potentiometer.
- **Compressor:** Automatically simulates increasing pressure.
- **LCD:** Displays target pressure, current pressure, and countdown.
- **LEDs:** Four LEDs display the countdown in binary from 10 to 0.
- **Completion:** Displays "SIM COMPLETE" when finished.

## Components
Arduino Uno, 16x2 I2C LCD, four LEDs, potentiometer, breadboard, and connecting wires.

## How to Run
1. Open the Tinkercad project.
2. Adjust the left potentiometer to set target pressure.
3. Start the simulation.
4. Wait for the pressure to reach the target and watch the countdown.

## Limitations
The compressor is simulated automatically. The second potentiometer and binary/hexadecimal pressure input are not yet implemented.
