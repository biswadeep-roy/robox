# robox
A small robotic car made using arduino


Aim:

The purpose of this project is to build an Arduino-based Bluetooth-controlled robot with an HC-05 module. Two motors on the robot can be controlled in order to move ahead, go backward, turn left, turn right, or stop. 
A further component of the project is an ultrasonic sensor, which can identify impediments in front of the robot and halt its motors if the distance is 20 cm or less. 
In order to try to eliminate impediments, a servo motor has also been added to the project, which causes the robot to move horizontally in response to commands.

These are some possible applications for a Bluetooth-controlled robot equipped with servo motors, ultrasonic sensors, and motor drivers are:
Surveillance: The robot may be used as a surveillance tool to keep an eye on a location and spot any intrusive activities. The servo motor may be used to move the ultrasonic sensor horizontally to cover a larger region. The ultrasonic sensor can detect the existence of an item in front of the robot. The robot may be set up to shoot photos or movies and Bluetooth-send them to the owner's phone.
Home automation: The robot may be employed to automate routine household duties like turning on and off the lights, opening and closing doors, and moving things. When the owner enters or exits the house, for example, the robot can be set to carry out these activities at predetermined intervals or in reaction to specified occurrences.
Agricultural automation: The robot may be utilised in agricultural automation to carry out duties like crop planting, watering, and harvesting. The farmer may use Bluetooth to direct the robot or configure it to travel to certain spots and carry out duties on its own.
Remote inspection: The robot has the ability to conduct remote inspections in risky or challenging-to-reach areas, such as tall buildings, pipelines, and electrical wires. The inspector's phone may receive wireless Bluetooth data from the robot's camera and other sensors regarding the area under inspection.
Environmental monitoring: The robot might be employed to monitor the temperature, humidity, and air quality in a specific area. Sensors aboard the robot may be used to measure these variables, and the owner's phone may get the data once it has been transferred through Bluetooth.

The Bluetooth-controlled robot's operation with servo motors, ultrasonic sensors, and motor drivers may be summarized as follows:
Motor Control: Motor drivers are in charge of the robot's two motors. The microprocessor sends orders to the motor drivers, instructing them on how quickly and which way to go.
Bluetooth communication: An HC-05 module is used to operate the robot through Bluetooth. The HC-05 module transmits commands to the microcontroller from a smartphone or other Bluetooth-enabled device.
Ultrasonic Sensor: The robot uses ultrasonic sensors to find obstructions along its path. It generates high-frequency sound waves and measures the elapsed time till the waves return. The robot's microprocessor calculates the distance to an object based on how long it takes the sound waves to return.
Servomotor: The robot also contains a servomotor that is used to move a sensor arm horizontally. The servo motor receives instructions from the CPU to travel at a specific angle, which causes the sensor arm to rotate and eliminate obstructions from the robot's path.
Obstacle detection: The robot stops going forward and the servo motor spins the sensor arm to remove the obstruction when an impediment is identified within 20 cm of it by the ultrasonic sensors. The robot continues to advance once the obstruction has been eliminated.
Power supply: The robot's microprocessor, motors, Bluetooth module, ultrasonic sensors, and servo motor are all supplied by a battery or an external power source.

The Bluetooth-controlled robot with motor drivers, ultrasonic sensors, and servo motors has various advantages, including:
Obstacle detection: The robot's ultrasonic sensors enable it to detect obstacles in its path and avoid collisions, making it safe to use in a variety of environments.
Efficient movement: The robot's motor drivers enable it to move efficiently and smoothly, which is important for tasks such as material handling and assembly line work.
Remote control: Bluetooth allows users to operate the robot from a distance. This can be helpful in circumstances where it would be challenging or hazardous for a person to be there.
User-friendly Control: The robot can be controlled with a smartphone or other he Bluetooth-enabled device, making it easy for both novice and experienced users.
![image](https://user-images.githubusercontent.com/74821633/236868660-581c31d7-fbcf-4792-aa05-28c0da4f8895.png)

Basic Connections
Set up the Arduino Uno 3
Motor 1 left is at pin number 4 and right is at 5
Motor 2 left = 6 & right = 7
Ultrasonic sensor trigger at pin 8 and echo is at pin 9
Bluetooth module RXD pin is at pin 1 and TXD is at 0
Servo motor’s Data Pin goes to A0
In the end we will give the power supply to Motor Driver and through motor driver we will give power to Arduino.
We will compile and upload the code to Arduino and run the robot
Then we will power up the robot and command it with our mobile device. Up arrow key means go forward. Side arrow key means the robot will go in that direction. Back arrow key will reverse it.
When the distance is 20cm or less the robot will stop automatically if not stopped. 

