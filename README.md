# Leap-motion-controlled-Drone 

Welcome to the Leap-motion-controlled-Drone wiki! Here we control a custom made tricopter using leap motion and hand movements. 

To run this app, node.js is required with additional plugins of ws ( for the leap motion ) and johnny five to allow the Arduino to interpret the javascript code. Control.js is the main file where all code is present, rest are supporting libraries.

The leap motion translates hand motions into servo movements for the Arduino to control the drone.  The standard firmata plus is uploaded on the arduino and then connected to with a serial cable to transfer the leap values. 


<img src="layout.png" width="350"/>

Addtionally the arduino is set up as the diagram below, with connections to three servos.

<img src="arduinosetup.jpg" width="350"/> 
Credits to http://marc-tetrapod.blogspot.sg/2012/10/arduino-ssc-32-servo.html for the image.

<img src="1.jpg" width="350"/> 
Final setup

