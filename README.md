Haptic Piano Project 

This project explores haptic rendering and force-feedback control through the development of a virtual piano key using the Longhorn Hapkit platform. Inspired by the force-feedback mechanisms used in robotic surgical systems such as the da Vinci Surgical System, the system recreates the tactile sensation of pressing a real piano key by combining mechanical design, sensor feedback, and real-time control algorithms.

The project involved designing custom piano key components, integrating them with the Hapkit hardware, and implementing software capable of generating realistic force responses during user interaction.

Objectives
Simulate the feel of a physical piano key using haptic feedback.
Model key stiffness and resistance through virtual spring-damper systems.
Investigate human-machine interaction through force rendering.
Apply mechatronics, embedded systems, and control theory concepts to a functional haptic device.


The Longhorn Hapkit consists of:

A DC motor used to generate force feedback.
A rotary encoder for position sensing.
An Arduino-based control system for real-time computation.
A cable-driven transmission mechanism connecting the motor and user interface.
An L298N motor driver for bidirectional motor control.

The motor and encoder continuously measure user input and apply calculated reaction forces to emulate the behavior of a piano key.

Design and Development
Mechanical Design
Designed custom piano key components using CAD software.
Manufactured and integrated the key mechanism with the Hapkit handle assembly.
Optimized geometry and travel distance to resemble the motion of a traditional piano key.
Developed mounting interfaces for seamless integration with the Hapkit transmission system.
Embedded Systems
Programmed the system using Arduino.
Utilized encoder feedback to track user input position in real time.
Implemented PWM motor control through the L298N motor driver.
Integrated sensor data acquisition and force computation within a high-frequency control loop.
Haptic Control
Developed force-feedback algorithms based on virtual spring and damping models.
Calculated interaction forces from encoder position measurements.
Rendered realistic key resistance and return forces through closed-loop motor control.
Tuned system parameters to improve stability, responsiveness, and realism.
Technologies Used
Arduino
C/C++
Longhorn Hapkit Platform
DC Motor and Rotary Encoder
L298N Motor Driver
CAD Design
Embedded Systems
Mechatronics
Haptic Rendering
Force-Feedback Control Systems
Outcomes
Successfully developed a functional haptic piano key capable of reproducing realistic tactile feedback.
Demonstrated the integration of mechanical design, electronics, sensing, and control systems into a unified mechatronic platform.
Gained experience with haptic interface design principles used in advanced robotic and surgical systems.
