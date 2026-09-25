# Audio Amplifier 

A custom Audio Amplifier PCB designed using KiCad.

## Overview

This project contains the schematic and PCB design for an audio amplifier
circuit. The PCB includes an audio input, volume control, amplifier section,
power connections, and audio output.

The complete board was designed using KiCad, including schematic capture,
component footprints, PCB routing, and 3D visualization.

## Features

- Audio input through audio jack
- Volume control using potentiometer
- Audio amplification circuit
- Power supply connection
- Audio output connection
- Custom PCB layout
- KiCad schematic and PCB files
- 3D PCB visualization

## Software

- KiCad
- KiCad Schematic Editor
- KiCad PCB Editor
- KiCad 3D Viewer

## Components

The project includes components such as:

- Audio Jack
- Potentiometer
- Amplifier IC
- Resistors
- Capacitors
- Power connector
- Audio output connector

## Audio Input

The audio input uses a 3.5 mm audio jack.

The jack provides:

- Tip – Audio signal
- Ring – Additional audio contact
- Sleeve – Ground/reference

The Ring connection is left unused in this design and is marked as
**No Connect** in the KiCad schematic.

## PCB Design Process

The PCB was developed using the following steps:

1. Create the circuit schematic.
2. Assign footprints to the components.
3. Add 3D models where required.
4. Transfer the schematic to the PCB Editor.
5. Place the components.
6. Route the PCB tracks.
7. Check the PCB layout.
8. Run the Design Rules Check (DRC).
9. View the completed PCB using the KiCad 3D Viewer.

## Project Files

```text
Audio Amplifier/
│
├── Audio Amplifier.kicad_pro
├── Audio Amplifier.kicad_sch
├── Audio Amplifier.kicad_pcb
└── README.md
