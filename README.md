# Collision Detection System 
This repo features the code, schematic and video demonstration of the prototype of a collision detection system. The components that where used in this project are:
* A 16x2 LCD display 
* 1.1k ohms resistor (R1)
* 3.9k ohms resistor (R2)
* 240 ohms resistor (R3)
* An ultrasonic sensor 
* An Arduino Uno 
* A Breadboard
* Jumper wires
* 4 LED's 

The system works by sending an ultrasonic pulse through the transmitter of the ultrasonic sensor. When it hits an objeact it is reflacted back to the reciever of the sensor and the distance from the object is calculated from the time it takes to recieve the echo. If the distance from the closest object infront of it is less than 3.3m, the system addresses the LED to start blinking. The closser the object, the faster the LED blinks to act as a visual indicator 