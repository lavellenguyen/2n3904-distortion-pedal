# 2N3904 Distortion Pedal

A single-transistor guitar distortion pedal built on breadboard, based on the 2N3904.

![Breadboard Build](breadboard-build.jpg)

## Overview
This project is a simple analog distortion effect for electric guitar, built around a single 2N3904 transistor in a common-emitter clipping stage, with diode clipping at the output for additional tone shaping.

## Schematic
![Schematic](schematic.png)

## How It Works
- **Input capacitor (47nF):** blocks DC and passes only the guitar signal
- **2N3904 transistor:** amplifies and clips the signal, creating distortion
- **220Ω resistor:** sets the transistor's bias point
- **4.7MΩ feedback resistor:** sets gain and stabilizes the bias
- **Output capacitor (47nF) + 50kΩ potentiometer:** controls output volume
- **1N4148 diodes:** add further clipping to shape the tone

## Components
| Component | Value |
|---|---|
| Transistor | 2N3904 |
| Resistor | 4.7MΩ |
| Resistor | 220Ω |
| Capacitor | 47nF (x2) |
| Potentiometer | 50kΩ |
| Diode | 1N4148 (x2) |

## What I Learned
- Hands-on experience with transistor biasing and signal clipping
- Breadboard prototyping and troubleshooting analog circuits
- How component values affect gain, tone, and distortion character
