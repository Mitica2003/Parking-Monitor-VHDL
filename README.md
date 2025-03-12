# Parking-Monitor-VHDL

## Overview

This project implements an intelligent parking occupancy monitoring system designed to track the availability of parking spaces in a rectangular parking lot with an even number of spaces. The system uses sensors to detect vehicle entry and exit and provides real-time updates on the number of available spots through a display.

## System Functionality

- **Vehicle Detection:** Each entry/exit has two optical sensors to determine the direction of movement and distinguish vehicles from smaller objects.
- **Display of Free Spots:** The system updates and displays the number of available parking spaces.
- **Control Mechanisms:** Includes a reset button to reset the parking count and LED indicators for full and empty parking states.

## System Design

- **Control Unit (UC) & Execution Unit (UE):** The system is divided into a control logic unit and resource execution unit.
- **Sensors:** Optical sensors detect vehicle movement at both entries and exits.
- **Counter:** Keeps track of available parking spots and updates the display accordingly.
- **State Diagram Representation:** Implements a structured flow for parking entry and exit processes.

## User Guide

- The parking system starts with all spots empty, indicated by an "Empty" LED.
- As vehicles enter, the spot count decreases, and the "Empty" LED turns off.
- When the parking lot is full, a "Full" LED indicator turns on.
- A reset button allows the system to restart the parking count.

## Future Enhancements

- Additional displays to show occupied spots.
- A timer to track vehicle parking duration and impose time limits.
- Improved object detection sensors to filter out small objects from being misidentified as vehicles.

## Conclusion

This project demonstrates an efficient way to monitor parking availability using a combination of sensors, control logic, and display units. The system can be further improved with additional features for enhanced automation and accuracy.

