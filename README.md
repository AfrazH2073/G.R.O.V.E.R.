# G.R.O.V.E.R. (Greenhouse Robotic Observer for Vegetation and Environmental Reporting)


## ECE/MAE 148 Team 8 Fall 2025 Final Project

Professor Dr. Jack Silberman

Lab Tutor: Winston Chou

Lab Tutor: Aryan _lastname_

Table of Contents


[TOC]



# Team Members

[Afraz Hameed](https://www.linkedin.com/in/afraz-hameed) - Computer Engineering, ECE 

[Hasaan Haq](https://www.linkedin.com/in/hasaanhaq/) - Computer Engineering, ECE

Marshall - Mechanical Engineering, MAE

Matt S. - Mechanical Engineering, MAE


# Abstract 

The goal of this project is to develop an autonomous rover that travels from a designated Point A to Point B using GPS-based navigation. At Point B, where a plant is known to be located, the rover automatically begins a multi-modal sensing routine. This routine includes capturing images of the plant for visual health assessment using the PlantCV library, inserting a soil probe to measure temperature and moisture, and collecting environmental data such as temperature, humidity, pressure, and gas metrics using the BME688 sensor. By combining these two sources of information, direct soil and environmental measurements and computer-vision-based plant analysis, the system acts as a remote autonomous plant-health monitoring platform and supports informed decisions about potential actions for the plant.


# What We Promised

Must Haves include:



* Have car be able to autonomously navigate using GPS from point A to point B
* Interrupt the GPS and use PlantCV to recognize the plant and guide the car for optimal destination to stop
* From a decided destination, unleashes a mechanism to probe the soil around the plant and gauge its temperature, moisture, etc.
* Utilize a Environmental sensor  that detects air humidity, temperature and pressure
* Utilizing ESP-32 and creating an application to remotely see data recorded

Nice to Haves include:



* Incorporate LiDar to detect obstructions more accurately
* Use ToF Sensor in tandem with LiDar for object detection


# Accomplishments


# Challenges



* Had a long time issue of Raspberry Pi module not being able to stay on while powered by LiPo Battery input to 5v DC/DC Converter
    * Had to change our Raspberry Pi after debugging and eliminating the below causes: 
        * Power
        * WiFi connection/connectibility
        * Faulty components / having to resolder components
        * Overwritten configurations /  having to try reconfiguring components
    * Many other kinds of issues until deciding to replace RPI, which then worked
* Had to split our team in two teams in Week 8 to complete work on another task alongside the final project (forgot the week)
        * One team to complete Path Following as it was pending completion
        * One team to gain progress on Final Project 

ADD CHALLENGES HERE AS WE HAVE THEM


# Final Project Video(s)


# Tech Stack


## Software



* PlantCV
* 


## Hardware



* Overall ECE/MAE 148 Project Components
    * Traxxas chassis
    * Brushless motor 
        * Hall effect sensor cables
        * Anti-slip clutch
        * Pinion
    * Raspberry Pi 5 
    * Servo Motors
    * Anti-Spark Switch
    * XT60 y splitter
    * XT30 y splitter
    * 5v DC/DC Converter
    * VESC Controller
    * OAKD Lite Camera
    * Pointone Nav GPS Module
        * Adapter Cable
        * Antenna
    * USB Hub
    * USBC Cables
    * Microusb Cables
    * Logitech Game Controller
    * Battery Alarm
    * Car Stand
    * uSD card(s)
    * SD to uSD adapter
* G.R.O.V.E.R. Specific Components
    * Adafruit BM 
    * Adafruit BME688 Environmental Sensor
    * Adafruit VL53L1X Time-of-Flight Sensor
    * DFRobot Capacitive Soil Moisture Sensor
    * Adafruit DS18B20 Waterproof Temperature Probe


## Mechanical


# Gantt Charts


## Starting Gantt Chart


## Current Gantt Chart


# Course Deliverables



* DonkeyCar Reinforcement Laps
* Line Following
* Lane Following
* GPS Laps
* Weekly Status Updates
* Final Presentation


# Project Reproduction


# Acknowledgements



* Documentation inspired by/directly referenced from [Team 7 - Winter 2024](https://github.com/UCSD-ECEMAE-148/winter-2024-final-project-team-7?tab=readme-ov-file)’s GitHub [ReadMe.md](ReadMe.md) file
* Immense gratitude to:
    * EnVision MakerStudio for allotting us to use their space, tools, resources, and generous staff for support on making this project come to life
    * Design Innovation Building’s MakerSpace for use of 3D printers and other tools to construct and configure components/parts needed for our project’s success
    * Triton AI for the support of their members via their space, tools, and resources to support us on this project
    * UCSD’s Mechanical & Aerospace Engineering Department for allotting us to use their courtyard for our Deep Learning Laps and Path Following Laps Course Deliverables
    * Fall 2025 ECE/MAE 148 Staff team including Jack Silberman, Winston Chou, and Aryan for the frequent support, advice, and mentorship they have provided us during the course of this quarter
    * All future engineers reading this documentation- whether taking this as inspiration for your own project or not
