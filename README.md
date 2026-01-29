# Joystick-Controlled Tilt Maze
## Overview

This project is a physical tilt-controlled maze game where a joystick is used to control two servo motors that tilt the maze along the X and Y axes. By adjusting the tilt, the player guides a ball through the maze to the goal.

Date Started: December 5th 2024

Date Finished: December 28th 2024

This was my first IoT/hardware project, built under a short time constraint, and it introduced me to mechanical control, real world constraints, and physical interaction design.

## Project Goal

The objective was to design an interactive system that:

Converts joystick input into mechanical motion

Uses servo motors to control tilt in two axes

Creates a responsive, intuitive physical game

## How It Works

A joystick provides two-axis analog input (X and Y)

The Arduino Uno reads joystick values

Two servo motors rotate accordingly

Servo motion tilts the maze platform in real time

The challenge was achieving smooth and stable motion while keeping the system mechanically balanced.

## Hardware Used

Arduino Uno

Analog joystick module

2× servo motors

Maze platform (custom-built)

Mechanical mounting components

## Software

Platform: Arduino Uno

Programming environment: mBlock

## Logic:

Read analog joystick input

Map values to servo angles

Apply limits to prevent mechanical strain

# Note: The original source code was created in mBlock and is no longer available. This repository focuses on the system design and behavior rather than code reuse.

## Build Process

Mechanical structure was assembled first to support two-axis movement

Servos were mounted orthogonally to control tilt

Joystick sensitivity was manually tuned through trial and error

Physical testing guided adjustments to angle limits

## Challenges & Constraints

Limited time required fast prototyping

Servo jitter and over-rotation had to be manually limited

Mechanical stability was more difficult than expected

Small changes in servo angles had large physical effects

## What I Learned

Physical systems amplify small errors

Mechanical design is as important as software

Input mapping must consider real-world constraints

Prototyping quickly is often better than over-planning

## Future Improvements

### If rebuilt today, I would:

Rewrite the control logic in Arduino C++

Add smoothing or PID control

Improve mechanical rigidity

Add sensors to detect maze completion

## Media

[Video Link](https://youtu.be/19fVoDeUWTA)

## Why This Project Matters

This project was my entry point into hardware and IoT systems. It laid the foundation for later projects involving sensors, actuators, and interactive physical systems.
