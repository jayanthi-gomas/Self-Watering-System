### Current project status: Almost completed

# Self Watering System (Raspberry Pi)
In this project we have planned to create a self watering system. The reason we want to create this is to find a solution on how we can go on vacation, and come home to plants that are still alive because of regular watering.

The idea is to measure the moisture in the soil to find out if the plant need more water. Based on how moist the soil is, a valve will open that water for x number of seconds before turning off again.

Thinking: If the moisture level is lower than X -> Open the water valve/run a water pump for X number of seconds.

Our team have never create a project like this before, so we are looking forward to continue on the project.

## Goals of our project
- Setting up the raspberry and connect the soil moisture sensor 
- Get values from the soil moisture sensor through the raspberry 
- Create a source code that opens a valve/run a water pump based on the value from the soil moisture sensor 

## Goals related to Blynk
 - Implement the Blynk application into our code so that we could see the soil moisture levels on our phones
 - Implement a function that open the valve/run a water pump through the Blynk application
 - Implement a function that read temperature and display it on Blynk
 - Implement a function that check the battery status and display in on Blynk 
 - Check the amout water that is in the container (extra sensor, watersensor)
 
## Result
- Comming soon
- To us as developers: Create a video that shows how the system works  

## Sources 
This is some of the sources that we have looked at before we have started our project.

- [Raspberry Pi Automated Plant Watering with Website](https://www.hackster.io/ben-eagan/raspberry-pi-automated-plant-watering-with-website-8af2dc?fbclid=IwAR2rEpD0V7SEx4g1vGgj0U8mOxeUxVy_Q9KWB-vI02odI4YQJSIKDzuGXjQ)
- [Raspberry Pi Automated Plant Watering with Website Video](https://www.youtube.com/watch?v=mQNJpWkdmbc&fbclid=IwAR2Lyb3M1nQq5Sxov5kAUKKsR2CUb9sm5UqoXmdDzFW9va9EiDJQGwjvSc0)
- [Automated Plant Watering with a Raspberry Pi](http://www.cyber-omelette.com/2017/09/automated-plant-watering.html)
- [Soil Moisture Sensor (Raspberry Pi) Video](https://www.youtube.com/watch?v=9LxrX5Eeukg&fbclid=IwAR0FE4Wo4NlOYpyUm4fB3W9ZQpody4zdgLYMwzWjMiEy8pgzE_xLgZLLtiQ)
- [Soil Moisture Sensor](http://www.piddlerintheroot.com/soil-moisture-sensor/)

## Equipment
- Raspberry Pi 3b +                              
- Jumper cables
- Soil moisture sensor
- Water pump
- Water container                                                         
- PVC tube
- Blynk Application

In addition to this equipment, we are going to use our own laptops (pc and mac) as well as our phones (IOS - iPhones). 
We also had a monitor, keyboard and mouse to work directly on the Pi.

## DIY project guide
Create this project yourself with the help of you guide that can be found in our Wiki-pages. As well as through this link: [DIY (Do it yourself)](https://github.com/nokaas/Self-Watering-System/wiki/DIY-(Do-it-yourself-guide))

## Picture that illustrates the project
![Attempt22](https://user-images.githubusercontent.com/35767860/67791761-4f011000-fa78-11e9-8109-9c9f839a6f58.jpg)

## Attempts 
To develop this project, we had to give it two different attempts to get it all working. This is written more about in the Wiki-pages. Here are the links to our two attempts: 
- [Attempt 1 (fail)](https://github.com/nokaas/Self-Watering-System/wiki/Attempt-1-(Fail))
- [Attempt 2 (successful)](https://github.com/nokaas/Self-Watering-System/wiki/Attempt-2-(Successful))


### Programming Planty.py
To get this project to work we had to do some programming. We did this by using the Python IDLE that comes with the Raspberry Pi. To start off this process, we did reasearch on how simular projects had been completed. The code that we generated is based on some of the projects that we found online, and the links for the inspiration are below: 
- [IoT Plant](https://github.com/Cakhavan/IoT_Plant/blob/master/Planty.py)
- [Turning on an LED with your Raspberry Pi](https://thepihut.com/blogs/raspberry-pi-tutorials/27968772-turning-on-an-led-with-your-raspberry-pis-gpio-pins)

Our source code is created by testing and trying different things, in the spirit of the term "learning by doing". We think it worked quite well. Take a look at the source code here:
- [Planty.py - source code](https://github.com/nokaas/Self-Watering-System/blob/master/src/soil%20moisture/Planty.py)

## Developers
[Aas, Knut Andreas](https://github.com/nokaas) 

[Andreassen, Jarl](https://github.com/Genijarl)
 
[Mathisen, Vegard Saavesen](https://github.com/vegardmathisen)
  
[Pedersen, Eivind](https://github.com/eivped)
