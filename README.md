# robox
a small robotic car made using arduino


Aim:

The purpose of this project is to build an Arduino-based Bluetooth-controlled robot with an HC-05 module. Two motors on the robot can be controlled in order to move ahead, go backward, turn left, turn right, or stop. 
A further component of the project is an ultrasonic sensor, which can identify impediments in front of the robot and halt its motors if the distance is 20 cm or less. 
In order to try to eliminate impediments, a servo motor has also been added to the project, which causes the robot to move horizontally in response to commands.
![image](https://user-images.githubusercontent.com/74821633/236867518-0e08689a-3ce7-4ff8-a57b-4a958dd592f8.png)



Materials required to build the remote controlled robot with an ultrasonic sensor, servo motor, and hand![image](https://user-images.githubusercontent.com/74821633/236867556-39c9f5c9-4b66-4dee-ac2c-07089cad8977.png)

Arduino board (Arduino Uno)
Ultrasonic sensor (HC-SR04)
Servo motor (sg 90)
Bluetooth module (HC-05)
DC motors and wheels
Motor driver (L298N)
Jumper wires
Lemon LiPo battery
Breadboard
Chassis
![image](https://user-images.githubusercontent.com/74821633/236867592-8ba860ae-4d22-4c7d-b236-c9c66f892b88.png)


Uses![image](https://user-images.githubusercontent.com/74821633/236867715-30d3e6c2-9ff2-426d-a51f-d46b7e72fb68.png)

These are some possible applications for a Bluetooth-controlled robot equipped with servo motors, ultrasonic sensors, and motor drivers are:
Surveillance: The robot may be used as a surveillance tool to keep an eye on a location and spot any intrusive activities. The servo motor may be used to move the ultrasonic sensor horizontally to cover a larger region. The ultrasonic sensor can detect the existence of an item in front of the robot. The robot may be set up to shoot photos or movies and Bluetooth-send them to the owner's phone.
Home automation: The robot may be employed to automate routine household duties like turning on and off the lights, opening and closing doors, and moving things. When the owner enters or exits the house, for example, the robot can be set to carry out these activities at predetermined intervals or in reaction to specified occurrences.
Agricultural automation: The robot may be utilised in agricultural automation to carry out duties like crop planting, watering, and harvesting. The farmer may use Bluetooth to direct the robot or configure it to travel to certain spots and carry out duties on its own.
Remote inspection: The robot has the ability to conduct remote inspections in risky or challenging-to-reach areas, such as tall buildings, pipelines, and electrical wires. The inspector's phone may receive wireless Bluetooth data from the robot's camera and other sensors regarding the area under inspection.
Environmental monitoring: The robot might be employed to monitor the temperature, humidity, and air quality in a specific area. Sensors aboard the robot may be used to measure these variables, and the owner's phone may get the data once it has been transferred through Bluetooth.
![image](https://user-images.githubusercontent.com/74821633/236867769-29451bfb-0936-4166-9e4c-51094e93bf7e.png)



Working![image](https://user-images.githubusercontent.com/74821633/236867795-4e9677c9-02b9-4626-a96e-0bf048b28d35.png)

The Bluetooth-controlled robot's operation with servo motors, ultrasonic sensors, and motor drivers may be summarized as follows:
Motor Control: Motor drivers are in charge of the robot's two motors. The microprocessor sends orders to the motor drivers, instructing them on how quickly and which way to go.
Bluetooth communication: An HC-05 module is used to operate the robot through Bluetooth. The HC-05 module transmits commands to the microcontroller from a smartphone or other Bluetooth-enabled device.
Ultrasonic Sensor: The robot uses ultrasonic sensors to find obstructions along its path. It generates high-frequency sound waves and measures the elapsed time till the waves return. The robot's microprocessor calculates the distance to an object based on how long it takes the sound waves to return.
Servomotor: The robot also contains a servomotor that is used to move a sensor arm horizontally. The servo motor receives instructions from the CPU to travel at a specific angle, which causes the sensor arm to rotate and eliminate obstructions from the robot's path.
Obstacle detection: The robot stops going forward and the servo motor spins the sensor arm to remove the obstruction when an impediment is identified within 20 cm of it by the ultrasonic sensors. The robot continues to advance once the obstruction has been eliminated.
Power supply: The robot's microprocessor, motors, Bluetooth module, ultrasonic sensors, and servo motor are all supplied by a battery or an external power source.
![image](https://user-images.githubusercontent.com/74821633/236867825-093d8af2-99e8-496f-aded-d557c4a7bf2d.png)


Benefits![image](https://user-images.githubusercontent.com/74821633/236867852-c290015f-cf88-415e-a7b2-48deb04d7470.png)
The Bluetooth-controlled robot with motor drivers, ultrasonic sensors, and servo motors has various advantages, including:
Obstacle detection: The robot's ultrasonic sensors enable it to detect obstacles in its path and avoid collisions, making it safe to use in a variety of environments.
Efficient movement: The robot's motor drivers enable it to move efficiently and smoothly, which is important for tasks such as material handling and assembly line work.
Remote control: Bluetooth allows users to operate the robot from a distance. This can be helpful in circumstances where it would be challenging or hazardous for a person to be there.
User-friendly Control: The robot can be controlled with a smartphone or other he Bluetooth-enabled device, making it easy for both novice and experienced users.
![image](https://user-images.githubusercontent.com/74821633/236867877-c1dfc357-6950-4bdf-a642-1daf00729d3a.png)


Cost Breakdown![image](https://user-images.githubusercontent.com/74821633/236867895-0181a9b4-fc97-44b1-8578-2b5159e70e6e.png)

A Chassis including 2DC motors and rubber wheels  costs around – 200 to 300Rs. The robot will require at least two motors in order to move. Chassis is required to install its parts and safeguard its electronics
A Battery to use in the robot ranges between 600 to 700Rs as inn order to run the robot's motors and other parts, it needs a power source.
A good quality Arduino costs  800 to 1000Rs. It is the brain of robot which will control individual parts.
An Ultrasonic Sensor will cost about 200Rs. The robot will require ultrasonic senor for detecting obstacles and avoiding collisions, which can help to ensure the safety and reliability of the robot
A Caster wheel to help with the movement of robot will be around 150Rs.
L298N will cost around 400Rs. It is motor driver which will control the motor speed.
Jumper Wires costs between 100-150Rs. To make connections between different components.
A good quality Servo Motor is around 350Rs. The servo motor can be used to control the movement of a hand or other mechanism attached to the robot, allowing the robot to pick up and move small objects out of its way
![image](https://user-images.githubusercontent.com/74821633/236867928-a379977c-b5c1-4f96-bd40-457000761b96.png)


Basic Design![image](https://user-images.githubusercontent.com/74821633/236867992-dd4ccc57-7bb4-4f5a-b2dd-67fd7d4ee582.png)

![image](https://user-images.githubusercontent.com/74821633/236867960-faf499cf-d560-4cec-801e-724ba09c13d0.png)

Basic Connections![image](https://user-images.githubusercontent.com/74821633/236868010-38aef19a-b3e4-41f2-b6bd-7deb445532d0.png)

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
![Uploading image.png…]()
