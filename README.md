# vision_based_robot
Using Open CV we made a robot which can detect a yellow ball and follow it.

Components Used:
BO Motors
Raspberry Pi3
L298N Motor Drivers
PiCamera
Power Bank
Chassis
LiPo Battery
Jumper wires

The basic body of the bot is provided by the chassis. 
The locomotion is given by the wheels using BO motors. 
The motors are controlled using motor drivers which in turn is controlled using the Raspberry Pi 3 using the GPIO pins.
The motor driver used is L298N. PiCamera is used to help the bot see its surrounding.
It is connected to the Pi to which it sends data. Raspbian OS is installed onto a SD card inserted in pi.
The entire code is written Python. The code analyzes the input from PiCamera and detects the yellow ball in the frame the PiCamera 
has captured,then it will move forward, towards the ball. Else it will keep rotating till it detects the ball.
