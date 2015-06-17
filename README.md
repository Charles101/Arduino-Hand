# Arduino-Hand
this project will involve a 3D printed Robot hand being controlled with a Cyberglove that is connected to the Arduino board

the idea for this project is to allow the user to gain control over the robotic prosthetic arm/hand, allowing to correspond with the user’s hand movement  to resemble the movement of  a human being. 

Over the years, the machines are being controlled using different ways of controls that help ease any hard work that may be difficult to any human based on their working abilities so as the years past different methods of controls are being used, but the most used control based on my opinion are levers and electrical controls, but what if there was another way to control specific machines using a cyber-glove and that when I had the idea.
In addition, the reason why this project was chosen was how machines work, especially robotics can move and think like humans, to interact like us and to operate on its own, I find project very interesting to program and it might be a challenge that I will enjoy.

# Hardware
The main components that was used to create the cyberglove and give the hand its movements, they are as listed:
.Flex sensor
.Servos (Tower Pro MG996R)
.Arduino Board UNO R3

# Flex sensor
These components are thin out sensors that can detect any amount of deflection that is caused by bending the flex sensors. With these flex sensors it can sense the bending depends on its angle that is bent from one point of the sensors. According to sensorwiki.org,,,“the smaller the radius and curvature and the more the whole length of the sensor is involved in the deflection, the greater the resistance will be.
Its purpose for the sensors of this project is to detect the bending points of one’s finger, receives the resistance signal  and the more the sensor is being bent, the resistance will change, it can be measured once it is connected to the Arduino board with an analog inputs.

By applying the sensors with an analog input (the red wire will take the positive voltage, the black wire will take on the negative voltage while the blue wire will be used to connect to the Arduino board) into the breadboard, with resistors (properly 22k resistors) that will connect to the Arduino board and once it is connected it should allow me to control the Mechatronic fingers to follow my movements.

# Servos
the servos will be used to control each finger, by attaching the strings on two sides of the servo’s gears it will pull the strings that are attached to the finger (each servo will control one finger) it will be controlled by the cyber glove.
As one finger closes, the servo will turn and be pulling on the string, causing the robotic finger to follow on its movements and as once my finger is released, the servos will stop pulling and retract the finger back to its state.
The way that the servos work is that it will be given a command that is functioned by the servo receiving a signal from the flex sensor that attach to the cyber glove  from the Arduino board.

# Aruino Board UNO
The Arduino will be the main component that is needed for this to work; it will program and be connected to the servos, the breadboard and the Cyber Glove. It will give each component a command and will then execute the their program, but it will can be successful based on the pins that each component is allocated to, programming the input and output signals.

