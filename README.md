# Overview
This small project implements a controller board intended for use in DIY flight simulator cockpits. The goal of the project is to create a versatile
hardware component suitable for a variety of simulated instruments (from buttons, dials and lights to glass cockpits), using a common bus 
interconnect and a common programming model and environment.

# Basic Requirements
- Flexible I/O (3.3 V digital I/O, high current H-bridge for stepper motors, analog input for sliders and potentiometers).
- Raspberry Pi CM4 connectors with HDMI/USB and parallel display connectors for resolutions (320x240 to 4k)
- RP2040 microcontroller for all low-spped I/O
- RS485 bus connector with integrated power supply via D-SUB-9 connector

# Current Project State
!!! EXPERIMENTAL, DESIGN ONLY !!!


Board Schematic:
[Schematic](/assets/FlightSimController-Schematics.pdf)

Redndered board view (front):
![Board-Front](/assets/FlightSimController-front.png)

Redndered bord view (back):
![Board-Back](/assets/FlightSimController-back.png)
