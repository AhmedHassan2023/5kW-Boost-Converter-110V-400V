# 5kW-Boost-Converter-110V-400V
5kW Boost Converter (110VDC to 400VDC) for DC Bus Applications using STM32F030R8T6 with Closed-Loop Voltage Control.

## Overview

This project presents the design and implementation of a 5kW boost converter intended to interface a battery charger with a high-voltage DC bus feeding a single-phase inverter.

The converter operates in closed-loop mode to maintain a regulated 400V DC bus under varying load and input conditions.

---

## Specifications

| Parameter | Value |
|-----------|-------|
| Input Voltage | 110 VDC |
| Output Voltage | 400 VDC |
| Rated Power | 5 kW |
| Topology | Boost Converter |
| Switching Frequency | 16 kHz |
| Control MCU | STM32F030R8T6 |
| Control Type | Closed Loop |

---

## Key Features

- Closed-loop voltage regulation
- High-power boost topology
- Custom magnetic design
- STM32-based digital control
- Signal-conditioning circuits
- Industrial PCB design
- UART communication interface

## Magnetics Design

The boost inductor was designed considering:

- Core selection
- Flux density verification
- Copper loss estimation
- Core loss estimation
- Thermal constraints

## Control Algorithm

- ADC acquisition
- PI voltage controller
- PWM generation
- Protection monitoring

## Technologies Used

- Power Electronics
- MATLAB/Simulink
- STM32
- Embedded C
- Altium Designer
- LTspice
- Magnetics Design
