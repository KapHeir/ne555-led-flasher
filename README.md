# NE555 LED Flasher PCB

This project is a simple NE555-based LED flasher PCB designed in KiCad.

## Overview

The circuit uses an NE555 timer in astable mode to blink 4 LEDs.  
The flashing speed can be adjusted with a potentiometer.

## Features

- NE555 timer based design
- 4 blinking LEDs
- Adjustable flash rate
- Through-hole components
- 2-layer PCB
- Designed in KiCad

## Power Supply

- Input voltage: 9V

## Main Components

- NE555P
- BC337 transistor
- 4 x LEDs
- 4 x 330 ohm resistors
- 1 x 1k resistor
- 1 x 10k resistor
- 1 x 100k potentiometer
- 1 x 10uF capacitor
- 1 x 100nF capacitor
- 1 x 10nF capacitor
- Terminal input connector
- SPDT switch

## Repository Structure

- `flasor.kicad_pro` — KiCad project file
- `flasor.kicad_sch` — schematic file
- `flasor.kicad_pcb` — PCB layout file
- `Gerbers/` — manufacturing files

## Manufacturing Files

Gerber and drill files are available in the `Gerbers` folder.

## Notes

This is a beginner PCB design project created for learning schematic capture, PCB layout, routing, and manufacturing file generation in KiCad.
