
IOT based Automated Street Light

The Street Light System:

The street light is used to illuminate the path for the traffic and pedestrians so that they can move safely in the dark slots of the environment. The street light automation concept is to optimise the illumination of the system to best guide the traffic and saving energy as well. Also there is a feedback system which will alert the central office for any kind of failure or tampering of the each individual street light. All street lights are mapped with the co-ordinates of individual lights onto the google map, at the time of their installation. This mapping of the street lights on the google map will show the status of the individual lights through symbol colour, which will help central office to understand better about the present status of the system. On-Off of the street light is driven by the co-ordinate of the individual light on the earth surface, and according to the sunlight available on the place at the moment. In the daytime, the illumination is also controlled by the present status of the weather. The optional feature of the machine learning and Al can be incorporated in the system, which will give better control on the operations of the street lights. 

The Roadmap designed to realise the above proposed system:

1. The street lights with the capacity of 25 Watts to 200 Watts can be used according to the installation requirements. 2) The street lights will be dimmable to give control on the illumination from 5% to 100%. 3) There will be two kinds of the street lights namely "Master" and "Slave", where in a cluster of the street lights, there will be one "Master" and all others will be "Slave". 4) Any street light can be made "Master" or "Slave" by replacing its control module. 5) All "Slave" Street lights are connected to "Master" with the RF mesh network. 6) The "Master" is connected to the software called Central Controlling Software (CCS) present on the cloud, using the 4G/2G network. 7) All the street lights will be having the ultrasonic sensors to sense the traffic or pedestrian. Which will guide street lights to properly illuminate the path. 
    
2. All the street lights are programmed with co-ordinates of the place at the time of installation. 9) The "Master" will generate the On Time and Off Time slab for all the street lights according to the sun light present on the location and current weather conditions. 10) All the street lights will illuminate the path according to the traffic conditions. 11) All the street lights will report the current operational status of the individual lights to the "CCS". 
    

Specifications of the Street light System:

The Street Light system is composed of five major components as follows:

1. Street Light
    
2. Control module
    
3. Software on the Control module
    
4. Software on the Cloud side
    
5. Cloud
    

The specifications of the automated street light system components will be:

1. Street Light:

a) The street light capacity - 25 W to 200 W (Selectable)

b) Input voltage - 180 V to 365 V ac

c) Dimmability - 5% to 100% using PWM signal

d) Power Supply - SMPS based on VIPER267K

2. Control Module:

a) Controllability of the street light - PWM of 10 kHz to control

dimming and Signal for the relay to switch on and off. 

b) Power Supply - Capacitive power supply

c) Input Voltage - 110 V to 440 V

d) Motion/interrupt Sensor - ultrasonic water proof sensor

e) Connectivity module - RF mesh module from Radiocraft

f) Cloud Connectivity ("MASTER" only) - EC200U (4G fall back

2G module) from Quectel

g) Microcontroller - MSP430F427 from Texas Instruments

h) Memory - AT24C256 8 pin SOIC from Atmel

i) LCD-18 Pin 7 segment LCD

j) Photo-sensor - TSL25203 from OSRAM ("MASTER" only)

k) Relay - 240 V ac, 5 Amps

3. Software on Control Module:

a) The software residing on the Control module is developed on the IAR environment in C language. b) The software is embedded into the microcontroller of the control module. c) For all kinds of the control module will detect the traffic condition and will generate the high beam on signal for the street light and produce the status of this information to send it to "MASTER" module. Where "MASTER" module will generate the high beam on signal to other "SLAVE" modules by calculating the speed of the vehicle. d) High beam will reset to low beam in one minute after getting no traffic or no pedestrian signal from the ultrasonic sensor. e) The Software will measure the input energy to the street light continuously and the demand of 15 minutes will be integrated and stored into the memory, to generate the logs of the energy consumption. f) The Software will also monitor the operational status of the street light by the measurement of the dc current drawn by street light to understand the failures of the system and generating the report to send it to "MASTER". g) The Software will optionally incorporate the machine learning methodology software which will predict the traffic conditions from the past learning and will generate high beam or low beam signals to control the street light illumination. h) The software will send relevant data to the "MASTER" using RF mesh network. i) The software incorporated in the "MASTER" will send the relevant data to the "CCS" residing on the Cloud using 4G/2G module via TCP/IP at ipv6 protocol. 

4. Software on the Cloud Side:

a) This software which is residing on the Cloud is called "CCS". b) This software is responsible to communicate with the street light control modules using high security TLS 1.3 encryption and decryption method. c) The "CCS" is using php and java languages to execute all the fuctions assigned to it. d) The "CCS" is getting current status of the street lights and will be mapped onto the google map. e) The "CCS will study the energy consumption, on-off and the high-low beam logs of the individual light and will generate the control strategy for the system.

f) The "CCS" will override the high-low voltage and high-low current strategies for the individual lights, according to configurations set by the central office.

g) The "CCS" will override the controllability by machine learning option set by the central office.

h) The "CCS" will generate the information to the central office to mark the failure of the street light/lights and the type of the problems.

i) The "CCS" will produce a bird's-eye view for the status of the street light/lights onto the google map.

j) The "CCS" will be able to generate reports for the energy consumption, status and failure of the individual street light/Cluster of the street lights. 

k) The "CCS" will collect the current weather status from accuweather.com for the "MASTER" location and the status will be transferred to it to generate proper on-off conditions for the "MASTER" and "SLAVE". I) The "CCS" will override the ON-OFF status of the street lights from the central office. 

5. Cloud:

a) The "CCS" will be residing on the best cloud platform of the world named AWS. Which is guaranteed to work perfectly for 99.9% of the time. b) The AWS is the best for its performance, superfast and fault-free platform. c) The AWS has specs - EC2 with linux, t2 - micro, Ubuntu with 32 GB memory space

d) This AWS EC2 Cloud is configured with "LAMP" (Linux, Apache, Mysql and PHP) server. e) The database will be managed by the MYSQL installed on the server, which can be configured by the "CCS".