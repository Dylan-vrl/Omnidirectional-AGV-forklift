---
title: Omnidirectional AGV forklift with QR code integration
author: Loïc Misenta, Hadrien Saigot Forest, Inés Araujo Cañas, Athena Papageorgiou Koufidou, Kalil Sama Bouzigues, Dylan Vairoli
date: 2023
---

# Omnidirectional AGV forklift using QR code recognition
[Watch it in action](https://www.youtube.com/watch?v=CywsanmOO58)

## Overview
This small-scale omnidirectional AVG forklift presents a simulation of larger-scale applications. Equipped with mecanum wheels, this forklift offers increased maneuverability, making it ideal for tight spaces. The integration of QR code reading capabilities allows the forklift to autonomously navigate and place boxes based on coded instructions. Users can also take manual control using either a gamepad or a web interface. 

## Components

### Microcontrollers
- 1x Arduino Uno
- 1x ESP32-CAM 
- 1x ESP8266

### Motors
- 5x NEMA17-04 stepper motors
- 5x A4988 stepper drivers
- 1x Arduino Uno CNC shield A4988

### Electronics
- 2x Omron SS-5GL
- 1x Toggle switch

### Power supply
- 1x Conrad Energy Lipo battery 11.1V 5000mAh
- 1x 5V to 10V battery

### Structure
- 1x Machifit 15pcs 400mm Optical Axis Guide Bearing Housings Linear Rail Shaft Support Screws Set

## Files
- The `.dxf` files for the MDF parts are in the `/dxf` folder
- The `.stl` files for the 3D printed parts are in the `/stl` folder
- The scripts are all in the `/scripts` folder. 
  
## Related projects
Our project has been heavily inspired by the [Arduino Mecanum Wheels Robot](https://howtomechatronics.com/projects/arduino-mecanum-wheels-robot/) tutorial by Dejan. We used their design for the wheels.