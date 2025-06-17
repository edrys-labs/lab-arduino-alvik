# Arduino Alvik Lab

An interactive remote laboratory for programming the Arduino Alvik robot with MicroPython.

Import the lab into your Edrys classroom using the following link:

https://raw.githubusercontent.com/edrys-labs/lab-arduino-alvik/refs/heads/main/alvik_lab.yaml

or just click the deploy button below:

[<img src="https://img.shields.io/badge/%F0%9F%9A%80%20-%20Deploy%20Lab%20-%20light?style=plastic" height="25" />](https://edrys-labs.github.io/?/deploy/https://raw.githubusercontent.com/edrys-labs/lab-arduino-alvik/refs/heads/main/alvik_lab.yaml)

## Overview

This laboratory practicum offers students the opportunity to learn the basics of programming embedded systems with MicroPython – directly using the Arduino Alvik robot as an example. The lab is accessible as a remote laboratory through the Edrys platform, allowing students to experiment with real hardware from anywhere.

The connection to the Alvik robot is established via WebREPL, which is a standard for communicating with and controlling a MicroPython-based board over a web interface.

## Learning Objectives

- First steps in programming embedded systems with MicroPython
- Getting to know the hardware functions of the Arduino Alvik robot (sensors, motors, LEDs)
- Independent experimentation with robot functions such as driving, line following, obstacle detection
- Using the serial interface for communication and error analysis
- Development of structured, reusable programs in MicroPython

## Lab Structure

The lab is divided into several areas:

1. **Lobby**: Introduction and overview of the lab
2. **Room 1**: Basic information about the Alvik robot and learning objectives
3. **Station**: Practical programming with code editor, live stream of hardware and WebREPL terminal

## Requirements (WebREPL)

In order to start the WebREPL terminal and create a connection to the Alvik robot, follow the instructions in the [WebREPL module](https://github.com/edrys-labs/module-micropython-webrepl).

When **self_charge_alvik** is set to `True`, the Alvik robot will automatically drive to the charging station when all users have left the station. This is useful for ensuring that the robot is always ready for the next user.