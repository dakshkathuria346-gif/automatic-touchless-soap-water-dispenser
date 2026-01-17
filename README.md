Automatic Soap & Water Dispenser using Arduino

A smart hygiene system designed to provide completely touch‑free handwashing using Arduino and ultrasonic sensing. The system automatically dispenses soap followed by water when a hand is detected, ensuring improved sanitation and reduced water wastage.

Project Description

This project implements an automated hand hygiene solution using an Arduino UNO and an HC‑SR04 ultrasonic sensor. When a hand is placed within a predefined distance, the system activates relay‑controlled DC pumps to dispense soap and water sequentially.

### The design focuses on:

Contactless operation
Low‑cost hardware
Efficient water usage
Safe isolation between control and load circuits
__________________________
 
### Team Members

Daksh Kathuria
Bhavya Singla
Deepanshi Jindal
Shaurya (Suyash Dubey)
__________________________
 
### Components Used

Component	Quantity	Purpose
Arduino UNO	1	Main controller
HC‑SR04 Ultrasonic Sensor	1	Hand detection
Relay Module (5V)	2	Control pumps
Mini DC Pump	2	Soap & water dispensing
Battery Pack	1	External power for pumps
Breadboard	1	Circuit setup
Jumper Wires	—	Connections
__________________________
 
### Working Principle

Ultrasonic sensor continuously measures distance
Hand detected within threshold range
Arduino triggers Soap Pump via Relay
Short programmed delay
Water Pump activates automatically
Pumps stop after fixed time
System resets when hand is removed
__________________________
 
### Technical Concepts Applied

Ultrasonic distance measurement
Embedded automation using Arduino
Relay‑based load isolation
Sequential control logic
Practical application of:
KCL
KVL
Nodal & Mesh basics
__________________________
 
### Applications

Smart washrooms
Hospitals & clinics
Schools & labs
Public hygiene stations
Home automation setups
__________________________

### Limitations

Fixed dispensing duration
Sensor accuracy affected by angle
No refill level detection
Requires external battery maintenance
__________________________

### Future Scope

1.IoT integration (ESP8266/ESP32)
2.Adjustable dispensing
3.Liquid level sensors
4.Rechargeable power system
5.Compact enclosure design
__________________________

### Demo

Working video included in the repository.
__________________________
 
### Acknowledgment

This project was developed as part of our academic learning to implement real‑world embedded and automation concepts.

