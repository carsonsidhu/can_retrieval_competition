# Can Retrieval Competition Firmware
Firmware programming for an autonomous can-retrieval robot

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Features](#features)
* [Usage](#usage)
* [Project Status](#project-status)
* [Room for Improvement](#room-for-improvement)
* [Contact](#contact)
<!-- * [License](#license) -->


## General Information
This project is centred around developing firmware for a robot designed to navigate autonomously through a track and collect cans. Within this code is a PID control
algorithm used by a robot to adjust its position on track based on input from reflectance sensors. Furthermore, there are also methods implemented for 
can drop-off through the use of servomotors, as well as displaying messages on an OLED display.


## Technologies Used
- C/C++
- PlatformIO
- Arduino Framework
- Adafruit IO Library


## Features
List the ready features here:
- Easily adjustable parameters to change PID control values 
- Modular code to distinguish different use cases


## Usage
Upload code onto robot prior to competition, upon powering on, robot will run the script and begin driving!



## Project Status
Project is: Complete


## Room for Improvement
Room for improvement:
- PID controller can continue to be iterated and improved upon through experimentation
- Might find a way to drive robot faster through track 


## Contact
Created by [@carsonsidhu](www.linkedin.com/in/carson-sidhu-4b8464185) - feel free to contact me!
