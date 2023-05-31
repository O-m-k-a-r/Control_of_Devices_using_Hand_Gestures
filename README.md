# Control_of_Devices_using_Hand_Gestures
In this project we have tried building our own Gesture Control Laptop/Computer by combining the power of Arduino and Python.
We will use two Ultrasonic sensors to determine the position of our hand and control a media player (VLC) based on the position. 

Project Setup:-                                                 
The Trigger and Echo Pins of the first Ultrasonic Sensor, which is placed on the left of the screen, are connected to Pins 11 and 10 of the Arduino.                    
For the second Ultrasonic Sensor, the Trigger and Echo Pins are connected to Pins 6 and 5 of the Arduino.                                                       
Now, for the placement of the Sensors, place both the Ultrasonic Sensors on top of the Laptop screen, one at the left end and the other at right. We can use double sided tape to hold the sensors onto 
the screen.                                     
Now, the Arduino is placed on the back of the laptop screen. Then, connect the wires from Arduino to Trigger and Echo Pins of the individual sensor.
Finally, we will do the programming part of the project using Python.

Working of Project:-                          
1. Place your hand in front of the Right Ultrasonic Sensor at a distance (between 15CM to 35CM) for a small duration and move your hand away from the sensor. This gesture will Scroll Down the Web Page or Decrease the Volume.          
2. Place your hand in front of the Right Ultrasonic Sensor at a distance (between 15CM to 35CM) for a small duration and move your hand towards the sensor. This gesture will Scroll up the Web Page or Increase the Volume.                
3. Swipe your hand in front of the Right Ultrasonic Sensor. This gesture will move to the Next Tab.               
4. Swipe your hand in front of the Left Ultrasonic Sensor. This gesture will move to the Previous Tab or Play/Pause the Video.                        
5. Swipe your hand across both the sensors (Left Sensor first). This action will Switch between Tasks.

Project Materials:-         
Arduino:  Arduino is an open-source hardware and software company, project, and user community.                               
Ultrasonic Sensor: Measures the distance to an object using ultrasonic sound waves.                                   
Connecting Cable: Divided into compensating cables and extension cables.                            
Python: Python is used for hardware and software integration.                         
