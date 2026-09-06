# Digital AVR ATmega32 Control System

-------->>>   The code text:|  Src/Digital Menu(Code)/Debug/gl.c file  |   <<<--------

**Rotary Encoder Select & Toggle Controller and show in Graphical LCD**

A complete embedded system based on **ATmega32** microcontroller. The system allows the user to **select** between multiple relay outputs using a rotary encoder and then **toggle** the selected relay on/off by pressing the encoder button.

## Features
- Rotary encoder navigation for selecting items (relays)
- Pressing the encoder button **toggles** the output of the selected relay:
  - First press → Selected relay becomes **Active (ON)**
  - Second press → Selected relay becomes **Inactive (OFF)**
- Graphical LCD display for real-time status
- Designed and manufactured custom PCB using Altium Designer
- Programmed in C using CodeVision AVR

## How it works
1. Rotate the rotary encoder to **select** the desired relay (item).
2. Press the encoder button to **toggle** the output of the selected relay.
3. All status is displayed on the graphical LCD (on/off state, selected item, etc.).

## Hardware
- Microcontroller: ATmega32
- Input: Rotary encoder with button
- Output: Relays (multiple controllable relays)
- Display: Graphical LCD
- PCB Design: Altium Designer
- Compiler: CodeVision AVR
- Programming language: C

## Project Structure
