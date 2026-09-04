# Robotic-Arm-Prototype

## Brief Overview
Custom robotic arm prototype integrating CAD, 3D-printed components, servo motors, and Arduino control.

## WORK IN PROGRESS

![snapshot1](media/GIF/snapshot.gif)

## Project Goals
- Use stepper motors, belts, and pulleys to rotate joints under moderate load
- Design at least a 4 Degree of Freedom robotic arm prototype
- Be able to manually control the robotic arm and then move it with commands using inverse kinematics
- Build on CAD and learn how to design a robotic Gripper

## Mechanical Components
- 608 Ball Bearings
- 100x8 mm and 60x8mm steel rods
- idler pulley
- 20t, 60t, 80t pulley
- 6mm birchwood base
- M3 and M5 screws, nuts, and locknuts
- Closed-loop GT2 timing belts
- screw clamp housing piece

## Custom-designed mechanical components
- base1 (First base that is screw mounted on the birchwood)
- base2 (second base that is installed to the rotating base pulley)
- baes2 lid
- shoulder base (Supports the shoulder joint)
- Shoulder Arms
- Forearms
- Wrist
- Gripper (WIP)

## Electronics
- Arduino UNO R3
- NEMA 17 Stepper motors
- CNC shield
- MG90 metalgear servo
- limit switches
- MG996R servo
- Buck Converter

## Software
- Arduino IDE
- Autodesk Fusion

## How does it work?
Stepper motors are energized and drives a pulley using a pulley reduction to rotate the joint and lift the arm.
Version one will simply be manual control using potentiometers and buttons for each degree of freedom
Version two will implement movement using commands via inverse kinematics
 
  
  
