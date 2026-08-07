# Task:  Servo Motor Sweep

## Description

This project simulates four Servo Motors using Arduino Uno in Tinkercad.

The program performs two sequential movements:

1. All four servo motors move using the Sweep motion for 2 seconds.
2. After the 2 seconds finish, all servo motors stop and remain fixed at a 90° angle.

## Components

- Arduino Uno
- 4 Servo Motors
- Jumper Wires

## Circuit Connections

| Servo Motor | Signal Pin |
|-------------|------------|
| Servo 1     | D3         |
| Servo 2     | D5         |
| Servo 3     | D6         |
| Servo 4     | D9         |

All servo motors share:
- VCC → 5V
- GND → GND

## How It Works

1. The Arduino initializes all four servo motors.
2. The motors perform the Sweep movement together for 2 seconds.
3. When the 2 seconds end, all motors move to 90°.
4. The motors remain fixed at 90° until the simulation stops.

## Software

- Tinkercad
- Arduino IDE (Text Mode)

## Files

- Arduino Code
- README.md

## Result

The simulation successfully controls four servo motors simultaneously. The motors perform the Sweep movement for two seconds, then stop together at a 90° position as required.

## Screenshots

Add screenshots of:
- The Tinkercad circuit.
- The simulation while the servo motors are moving.
- The final position where all servo motors stop at 90°.
