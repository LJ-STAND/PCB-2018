# PCB 2018

This repository contains the PCB design files for the LJ STAND 2018 robot. They were produced using Autodesk EAGLE.

**There are the following boards in the ```LJ STAND``` directory:**
- Encoder - this is a hall-sensor based encoder for the robot wheels. Each wheel has alternating polarity magnets that trigger the sensors.
- Gyro MPU9250 - this is a breakout board for a fusion of 3 MPU9250 sensors. This was done to compensate for drift
- Gyro - an older design of the IMU breakout board using a different sensor
- Laser Mount - mount for the laser in a light-gate module
- Light - a 48-sensor circular reflective-light sensor array, used for detecting the position of a white line
- Main - main processing board, housing the microcontrollers, camera, power supply, motor driver modules and IR sensors for the ball
- MPU9250 Adapter - can replace the IMU breakout board with a single off the shelf MPU9250 breakout
- Phototransitor Mount - mount for the phototransistor in a light-gate module