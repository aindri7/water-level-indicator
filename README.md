# Design of Water Level Indicator along with Automatic Water Pump Control System
The project is designed to give a display of water level in a tank and control a pump motor as required. 
## Introduction
In accordance with the current scenario, a lot of water is wasted everyday from residential areas, offices and hospitals. Water is essential in various ways and such a huge amount of water wastage can lead to its scarcity in future. Nowadays everybody has overhead tank at their homes. Our objective is to indicate water level and control the water pump to avoid overflow of water. The idea can be implicitly used to ascertain and control the level of water in overhead tanks and prevent wastage. Microcontrollers offer  better solution, being  computers on single  chips;  enable  production  of  embedded  smart  systems  which  are  prevalent  everywhere  today. A  designer  just  need  to  master  it,  learn  their  instruction  sets  and  write  codes  that  make  them  work.  This project will allow the level of water in a tank to be maintained automatically, that is, unattended to; it uses Arduino microcontroller, codes were written in order for it to perform as water level controller.
## Componenets Required
All the required components are:
1) MICROCONTROLLER
2) LCD DISPLAY (16 × 2)
3) ULTRASONIC SENSOR MODULE
4) RELAY (6 V)
5) BUZZER
6) ULN2003
7) MINI MOTOR PUMP
8) RESISTORS
9) LED INDICATORS
10) 9V BATTERY OR 12V ADAPTOR
11) VOLTAGE REGULATOR (7806)
## Flow chart
![Screenshot (3) SS](https://github.com/aindri7/water-level-indicator/assets/75011539/012c3a8d-162d-4475-b918-6a1934f91f44)
## Circuit diagram
![Screenshot (4) CIRCUIT](https://github.com/aindri7/water-level-indicator/assets/75011539/f385a912-7a60-43c7-94e1-25e94e8c4c21)
## Working principle
This project is about water conservation which is the practice of using water efficiently to reduce unnecessary water usage and our motive is to do this job by using smart technology. If the tank is full then it will detect the situation by using ultrasonic sensor. And alert anyone by using buzzer. At first, we have to collect hardware. If the tank is full the ultrasonic sensor will activate. The LED will be off and the buzzer will work automatically. The motor will stop to save the water; water tank full, motor turned off will display on LCD screen. And in the second case if the tank is empty then the led will glow on the motor will start automatically; low water level, motor turned on will display on LCD screen. The buzzer will not work that time.
