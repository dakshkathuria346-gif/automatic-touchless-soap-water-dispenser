### Automatic Soap & Water Dispenser using Arduino

A smart hygiene system designed to provide completely touch‑free handwashing using Arduino and ultrasonic sensing. The system automatically dispenses soap followed by water when a hand is detected, ensuring improved sanitation and reduced water wastage.
__________________________

### Project Description

This project implements an automated hand hygiene solution using an Arduino UNO and an HC‑SR04 ultrasonic sensor. When a hand is placed within a predefined distance, the system activates relay‑controlled DC pumps to dispense soap and water sequentially.
__________________________

### The design focuses on:

1. Contactless operation
2. Low‑cost hardware
3. Efficient water usage
4. Safe isolation between control and load circuits
__________________________
 
### Team Members

1. Daksh Kathuria
2. Bhavya Singla
3. Deepanshi Jindal
4. Suyash Dubey
__________________________
 
### Components Used

1. Component	Quantity	Purpose
2. Arduino UNO	1	Main controller
3. HC‑SR04 Ultrasonic Sensor	1	Hand detection
4. Relay Module (5V)	2	Control pumps
5. Mini DC Pump	2	Soap & water dispensing
6. Battery Pack	1	External power for pumps
7. Breadboard	1	Circuit setup
8. Jumper Wires	—	Connections
__________________________
 
### Working Principle

1. Ultrasonic sensor continuously measures distance
2. Hand detected within threshold range
3. Arduino triggers Soap Pump via Relay
4. Short programmed delay
5. Water Pump activates automatically
6. Pumps stop after fixed time
7. System resets when hand is removed
__________________________
 
### Technical Concepts Applied

1. Ultrasonic distance measurement
2. Embedded automation using Arduino
3. Relay‑based load isolation
4. Sequential control logic
5. Practical application of:
6. KCL
7. KVL
8. Nodal & Mesh basics
__________________________
 
### Applications

1. Smart washrooms
2. Hospitals & clinics
3. Schools & labs
4. Public hygiene stations
5. Home automation setups
__________________________

### Limitations

1. Fixed dispensing duration
2. Sensor accuracy affected by angle
3. No refill level detection
4. Requires external battery maintenance
__________________________

### Future Scope

1. IoT integration (ESP8266/ESP32)
2. Adjustable dispensing
3. Liquid level sensors
4. Rechargeable power system
5. Compact enclosure design
__________________________

### Demo

Working video included in the repository.
__________________________
 
### Acknowledgment

This project was developed as part of our academic learning to implement real‑world embedded and automation concepts.

