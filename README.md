
# CS983: Embedded, Cyber Physical Systems and IoT Security

## Assignment: Build Your Smart Home



Project task is to build the Smart Home equipped with IOT technology sensors for Door automation, FAN speed regulation and Lumination of the LED 


## Description/Requirement

Jordan is a wealthy business tycoon who lives a life of indulgence and doesn’t shy away from an
extravagant display of his financial prowess. This time he has set his eyes on augmenting his home with
automation to improve his lifestyle, uplift his societal status, and feed his laziness. More specifically, Jordan wants to automate his door, fans, and lights. He contacted “Home Corp.”, a renowned smart-home startup, and finalized the lucrative deal. You are responsible for leading the project, and this is your time to shine and showcase your technical expertise.

You need an ultrasonic distance sensor installed on the door to detect if someone is at the door and a
servo motor to control the door movement. The house interior will have light sensors to see illumination
and lighting to toggle the light switch appropriately. We need to turn on the lights when Lux < 400 in the
room. A temperature and humidity sensor will detect how hot and humid the room is and regulate the fan
speed according to the table below. Please use this simulator to plan and execute your project.

Simulator: https://wokwi.com/projects/new/arduino-mega?template=arduino-mega

## Equipment Required from Simulator 

1. Temperature sensor and Humidity sensor
2. Servo motor
3. IR proximity sensor
4. Light sensor
5. Arduino board
6. Stepper motor
7. LCD Display
## Expected functionality

Expected functionality from your smart home simulation


1. Temperature and humidity(DHT22) sensor has sliders to adjust the readings. The fan speed(a stepper motor) should change with the change in temperature and humidity values according to the rules defined in the table above.
2. Turn ON the lights (LED) based on the illumination in the room. You can use LDR to measure illumination.
3. Use an ultrasonic distance sensor to detect the presence of a person at the doorway. When the measured distance is less than or equal to 200 centimeters,rotate the servo motor by 90-degree, simulating the motion of the door opening. After a certain period of time, initiate the closure of the simulated door by returning the servo motor to its original position.
4. Once the simulation has started, it should run in a loop. Reflecting any changes to the sensor values automatically by modifying the Servo motor position, LED state (ON, OFF) and display temperature and humidity values on LCD without restarting the simulation. Refresh the readings on the LCD in every iteration. You can use some delay time inside the loop so that displayed values don’t change too quickly
## Deliverables

1. Submit a report in pdf format mentioning how you have built the smart home system, the sensors used. Also, provide the link to your simulated project in the report (You can generate the link for your project from the simulator by signing in and saving the project).

2. The solution for the assignment should be submitted as a zip file. Please submit a single file per group.

3. Downloaded zip file of the simulation from the simulator (It should contain sketch.ino and diagram.json files).