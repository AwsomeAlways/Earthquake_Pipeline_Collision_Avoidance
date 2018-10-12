# Earthquake_Pipeline_Collision_Avoidance

Problem Statement - Bursting of Gas and other explosive pipelines during earthquakes.

Solution Developed : using GPS modules and Earthquake sensors to accurately pinpoint the location so as to raise alarms and switch off that areas during and after earthquake.

Method:
1. During the laying of pipelines, install gps modules with the pipeline which will determine its location and warn incase of any movement with the help of earthquake detection sensors and communication modules for each pipeline .
2. If an earthquake occurs, the earthquake detection sensors give output due to tremors. 
3. If the intensity of the earthquake is greater than a minimum threshold, we will program the system in such a way that it provides co-ordinates using the gps module and using principles of Internet of Things via the communication modules, it will  send the location co-ordinates to agencies to pin point the location.
4. Now, once we get the location, we can automate the task to automatically switch off the particular pipeline and also provide a remote manual option to the agency to control it manually if needed.
5. This will be highly useful to prevent any kind of explosion from taking place underneath and thereby prevent further aggravtion of damage to life and property hence save economic losses as gas can be immediately be shut down without much delay. 

For creating the prototype, we will be using arduino and breadboards for making the system .
Since for the protoype, communication will be limited to low range and we will use wifi modules.
The estimated budget will be under 10,000 rupees.
We can code the program in Arduino IDE and for sending any text use the reqd. libraries.
Materials Reqd-
1) Arduino Uno/Mega
2) Gy-NEO6MV2 	GPS Module
3) Battery Eliminator/ Alternative Power Sources
4) ESP8266 Wifi Module(integrated)
5) LEDs
6) Jumper Wires
7) Resistors
8) Earthquake Sensor(MPU6050 sensor)
9) LCD screen  
