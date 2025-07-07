# 5-degree-of-freedom-robotic-arm
Overview
This project features a 5 Degree of Freedom (DoF) Robotic Arm designed for basic pick-and-place operations, educational purposes, and light manipulation tasks. The arm's design focuses on simplicity, flexibility, and ease of control.

Features
5 Degrees of Freedom:

Base rotation

Shoulder movement

Elbow movement

Wrist rotation

Wrist pitch

Modular and extendable design

Lightweight and easy to 3D print

Suitable for small payloads and precise positioning tasks

Applications
Educational demonstrations

Simulation and control algorithm testing

Light-duty pick-and-place tasks

Prototyping for automation projects

System Components
Mechanical:
3D printed parts (or CNC, depending on your build)

Electronics:
Servo motors (5 units recommended)
Microcontroller (Arduino, Raspberry Pi, etc.)
Power supply appropriate for servo load

Control System:
Manual control via joystick
Pre-programmed sequence execution
Potential for integration with computer vision systems

Software Requirements
Arduino IDE or equivalent for microcontroller programming

(Optional) Python/ROS for higher-level control and simulation

Basic servo control libraries

Assembly Instructions
Print or fabricate all arm components.

Assemble joints using screws and/or bearings.

Mount servo motors in designated slots.

Connect servos to the microcontroller following the provided pin map.

Upload the control firmware to the microcontroller.

Power the system and begin calibration.

Usage
Manual Mode: Control the arm via joystick or input device.

Automated Mode: Run pre-written scripts to execute specific movement sequences.

Future Improvements
Add gripper for end-effector manipulation.

Integrate sensors for feedback (position, pressure, etc.).

Expand to 6 or more DoF for more complex tasks.

Implement inverse kinematics for precision path planning.

License
This project is open-source under the MIT License. Feel free to modify and share.
