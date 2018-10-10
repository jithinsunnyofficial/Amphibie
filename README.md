# Amphibie

Every year, natural disasters kill around 90,000 people and affect close to 160 million people worldwide. Humans have experienced or witnessed some dreadful natural disasters and unfortunately many were unable to overcome it because of the lack of effective disaster management systems. 

When a natural disaster strikes a populated area, rescue teams must get a quick overview of the situation to identify possible locations of victims, which need to be rescued, and dangerous locations, which need to be secured. 

It might take days for the rescuers to identify the exact position of the victims and implement the rescue mission. 

What if there was a robot which could help solve this problem? 

Staying close to the given challenge, our team’s main moto is to save people's lives and manage the impact of natural disaster. Our Robot - 'AMPHIBIE', helps in curbing the downtime which is required to find the missing victims during a natural disaster and provide the victims with essential help. 

AMPHIBIE is an all-terrain robot which can travel on land, water or in any harsh terrains. It has 4 subsystems in the main robot. Main-AMPHIBIE which is roughly of the dimension 60x25x60cm, having 4 Baby-AMPHIBIE of the dimension 15x10x8cm which is stored inside the Main-Robot. The body is made of plastic which helps the robot remain afloat. Arduino Mega and Raspberry Pi acts as the controller. The robot has a 4-wheel drive for a better efficiency on harsh terrains and specially designed wheels to navigate in water. 

AMPHIBIE can operate in Manual & Autonomous mode.

 In the “Manual-Mode”, the robot can be controlled using RF/Bluetooth/ Wi-Fi. In a situation where network is unavailable due to natural disaster, RF can be used to control the robot and has a range of 2kms. The robot can be controlled with Bluetooth if the area for search is within a radius of 100 m.  If there’s an internet connectivity during the disaster, the robot can be controlled using Azure where there’s no limit to the range. 
 
 In the “Autonomous-Mode”, the robot autonomously navigates to places and on reaching the destination, it begins its search mission.
 
 The Main-AMPHIBIE robot on reaching the destination releases its 4 Baby-bots which goes in different directions looking for people. It uses ultrasonic sound-based obstacle avoiding system and special algorithms to navigate. It uses thermal imaging to detect human’s presence in the affected areas. Once a human’s presence is detected, it sends a signal along with the GPS location to the main bot which sends it to Azure/receiver. The bots also send a live video streaming of its vision to the user. These bots can also detect if those places are safe for the rescue operation to be performed [by examining the air quality, light intensity, temperature, humidity and other parameters]. The bots also have special lights to perform operations in the night. These bots can also be used to send basic-necessities to the people struck at a place until the rescue operation arrives. 


