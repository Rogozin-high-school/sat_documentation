# Project Definition
All tasks, parts, TODOs and definitions for the whole project (software and hadrware)

## Magnetometer system
The system that detects the satellite's orientation in space, relative to the magnetic field.

### Software
1. Communication with the sensor.
2. Conversion of the data to usable vector-form data.

### Hadrware
1. Wiring of the sensor.
2. Adding the sensor to the 3D design of the satellite.

## Magnetorquers
The devices that exerts torque on the satellite using the magnetic field.

### Software
1. Communication with the power supplies for the torquers.
2. Conversion of math vector-form data to PWM signals for the torquers.

### Hardware
1. Enwrapping the torquers.
2. Inserting the torquers to the 3D design of the satellite.
3. Get bidirectional power supplies.
4. Connecting the torquers to bidirectional power supplies.
5. Wiring the power supply to the Raspberry Pi.

## Satellite Computer Module (SCM)
The system that will allow us to monitor and control the onboard equipment.

### Software
1. Implement the get commands that will allow us to control the magnetorquers.
2. Make a pretty ui for controlling the magnetorquers.

... (Todo - continue this document)
