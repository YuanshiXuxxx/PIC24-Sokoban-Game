# PIC24 Sokoban Game

An embedded implementation of the classic Sokoban puzzle game on a PIC24 microcontroller, featuring joystick input, LCD rendering, and modular peripheral control in C.

## Overview

This project implements a simplified Sokoban-style puzzle game on a PIC24 microcontroller.  
The system integrates joystick and button input with LCD output to create a responsive embedded gaming experience.

## Features

- Real-time joystick-based movement control
- Button-based interaction and input handling
- LCD rendering for game display
- PIC24 peripheral initialization and system setup
- Modular driver structure for hardware components
- Embedded game control on a resource-constrained platform

## Tech Stack

- C
- PIC24 microcontroller
- Embedded systems programming
- LCD interfacing
- Joystick and button input handling

## File Structure

- `pic24_init.c` — PIC24 initialization and core configuration
- `JoyStick.c` — joystick input reading and processing
- `Button.c` — button handling logic
- `LCD.c` — LCD communication and display control

## My Contributions

- Integrated joystick and button input into the game control flow
- Worked on LCD output and display updates
- Helped organize modular embedded source files
- Debugged hardware-software interaction on the PIC24 platform

## Project Goals

This project demonstrates:

- embedded C programming
- hardware-software integration
- real-time input handling
- modular peripheral driver development
- interactive system design on a microcontroller

## Future Improvements

- Add gameplay screenshots or hardware photos
- Add a block diagram / wiring diagram
- Document game logic in more detail
- Add setup instructions for the development environment
## 🔥 Key Highlights

- Designed and implemented a complete embedded game system on PIC24 (C-based)
- Built interrupt-driven input handling for real-time joystick and button control
- Developed core game logic including movement, collision detection, and win conditions
- Implemented LCD rendering pipeline with efficient screen updates
- Structured modular drivers for hardware abstraction and scalability
## 🧩 System Architecture
Input Layer (Joystick / Button)  
→ Interrupt-driven Input Handler  
→ Game State Machine (Logic & Rules)  
→ Rendering Layer (LCD Driver)
## 💡 Why This Project Matters

This project demonstrates the ability to build a complete embedded system integrating hardware input, real-time processing, and display output. It reflects practical experience in low-level programming and system design beyond standard coursework.
## 🧠 Engineering Takeaways

- Gained hands-on experience in real-time embedded system design
- Improved ability to debug hardware-software interaction
- Learned to structure low-level code into modular and maintainable components
- Developed understanding of resource-constrained system optimization

