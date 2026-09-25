# Audio-Amplifier

## Overview

This project is a custom PCB design for a small audio amplifier circuit. 
The PCB is designed using **KiCad** and contains the required audio input, 
amplifier circuitry, volume control, power connections, and output connections.

The main purpose of this project is to convert a low-level audio signal into 
a stronger signal that can be used to drive a speaker or other audio output.

## Features

- Audio input through a 3.5 mm audio jack
- Volume control using a potentiometer
- Audio amplification circuit
- Speaker/audio output
- Power supply connection
- Custom PCB layout designed in KiCad
- 3D PCB visualization
- Through-hole/SMD components depending on the selected design

## Software Used

- **KiCad** – Schematic and PCB design
- **KiCad PCB Editor** – PCB layout and routing
- **KiCad 3D Viewer** – PCB 3D visualization

Audio Input

The audio signal is supplied through an audio jack.

The audio jack contains:

Tip (T) – Audio signal
Ring (R) – Additional audio channel/contact
Sleeve (S) – Ground/reference connection

If the Ring connection is not required by the circuit, it can be left
unconnected and marked with a No Connect flag in KiCad.

Volume Control

A potentiometer is used to control the level of the audio signal before
amplification.

By rotating the potentiometer, the user can increase or decrease the
audio signal supplied to the amplifier.

PCB Design

The PCB was designed using KiCad.

The design process includes:

Creating the schematic
Assigning footprints
Adding 3D models
Creating the PCB layout
Placing components
Routing PCB tracks
Running Design Rule Check (DRC)
Viewing the final PCB in the 3D Viewer
PCB Layout

The PCB layout contains the components and copper tracks required to connect
the audio input, amplifier circuit, power supply, and audio output.

Care is taken during PCB layout to keep audio signal paths reasonably short
and to provide appropriate grounding.

3D Model

3D component models are assigned to the PCB footprints to visualize the
physical appearance of the completed board.

STEP (.step) models can be used for components when a KiCad-specific 3D
model is not available.

Testing

After fabrication and assembly:

Check the PCB for short circuits.
Verify the power supply connections.
Check component orientation and polarity.
Connect the audio input.
Connect the speaker/output.
Apply the required power supply.
Test the audio output.
Adjust the potentiometer to verify volume control.
Applications

This type of audio amplifier can be used in:

Small speaker systems
DIY audio projects
Electronic learning projects
Portable audio devices
Embedded audio systems
