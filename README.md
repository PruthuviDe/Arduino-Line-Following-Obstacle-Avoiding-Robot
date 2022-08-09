# <p align="Center"> <a href="https://www.arduino.cc/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" alt="arduino" width="25" height="25"/> </a>  Arduino Line Following And Obstacle Avoiding Robot


<div align="center">
<img src="https://raw.githubusercontent.com/Janith3003/Arduino-Robot/main/readme-essentials/LIFOD.jpg" width="300" height="auto">

</div>

#

The goal of this project is to build and develop a robot car using Arduino, that is able to follow a line, avoid obstacles if found while following the line and then come back to the original path. In this repository will be provided the whole code used to achieve the goal, the circuit diagram, and the libraries used for the Robot. About the hardware part: has been used an Arduino Uno as board, a Sensor Shield v5.0 and an L298N Dual Bridge, both optional, used to manage cables of wheels. A servo motor to rotate the ultrasonic sensor, an ultrasonic sensor to measure the distance from obstacles and two infrared sensor to track the line. If you wish to implement the code available in this repository make sure to tune parameters of the delay() functions in the code. Since the delay changes basing on the voltage of your batteries and the quality of your sensors, more or less delay will be needed to perform actions like a turn or any other movement.


##





* Requirement for Line Following And Obstacle Avoidance (remove Ultrasonic sensor for Line Follower): 

	- [x] x1 Arduino Uno  
	- [x] x2 Infrared Sensor (x3 ~ x5 for more accurate when tracking line and get back when move out from the track)  
	- [x] x1 9V Battery (or x2 Power Cell 18650 2000mAh) (or at least x4 Duracell AA 1.5V)  
	- [x] x1 9V Battery Clip (or Battery Box 18650 2 Cell (have switch))  (or Battery Box for AA Battery 4 Cell)  
	- [x] x1 Ultrasonic Sensor HC-SR04  
	- [x] x1 Motor Driver DC L298N  
	- [x] x1 Holder for Ultra Sonic Sensor HC-SR04 (or you can glue sensor to robot)  
	- [x] x1 Servo SG90 (for calculate the safest path to avoid obstacle) (optinal)  
	- [x] ~20-30 male-male jumper wires  
	- [x] ~20-30 male-female jumper wires  
	- [x] x1 Switch (if you don't buy a battery box have switch)  
	- [x] x1 Chassis (or DIY)  
	- [x] x2 Motor DC motor 12V  
	- [x] x2 Wheel  
  
  
  
  ## Project Simulation
  <img src='https://raw.githubusercontent.com/LikDev-256/Perseverance_2--Line_and_Wall_following-in-Webots/main/Videos/giphy.gif' width=650/>
  
  
  ## Schematics and circuit diagrams
  <a href="https://ibb.co/N2PsVVv"><img src="https://i.ibb.co/k2fxHH7/schematic-arduino-line-following-robot-sheet-u-Nr-Cjg-Bi-Re-1-cleanup.png" alt="schematic-arduino-line-following-robot-sheet-u-Nr-Cjg-Bi-Re-1-cleanup" border="0"></a>
  

  ## Special Thanks
  
- [Tharusha Perera](https://github.com/tharusha1004)
- [Janith Disanayaka](https://github.com/Janith3003)
- [Yasiru Ravishan](https://github.com/yasiruravishan24)

# References
  
  https://create.arduino.cc/projecthub/embeddedlab786/line-follower-robot-d22d06
  
