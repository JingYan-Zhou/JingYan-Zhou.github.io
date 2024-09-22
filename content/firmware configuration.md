+++
title = 'firmware configuration'
date = 2024-04-21T14:26:10+08:00
weight = 4
+++
## **Connecting raspberry pi to my computer**
Today I am going to start to do the most tedious part--connecting my raspberry pi to my computer and burning the programme into the SD card of the pi. I am choosing the operating system as other-RASPBERRY PI OS LITE (32-BIT). I am doing this according to the kiauh manual in github. After I have finished connecting it, I put the SD card into the pi, opened the battery sorce and tried to connect to it using the terminal in my computer. but becasue of Internet problems I could not connect to it succesfully, so I am going to try to connect it next time when I am using a different Internet, which should be better by then.
## **Sensorless homing with X and Y axis 1**
Because I only have sensors for my Z axis and E0 axis, which refers to the extruder axis, I will need to do some software and hardware installation to use sensorless homing for the other two, which are X and Y. I am using TMC2209, which has had it's sensorless homing opened. For my SKR Pico with Bigtreetech, I will have to put on two line-jumping hats. the situation varies from differents sensors and boards. I met a problem with differents things undefined in my documentation. I didn't happen to find the solution for it today.
## **Sensorless homing with X and Y axis 2**
I found which line of the documentation was wrong and crossed it out. Now I have successfully homed all of my axes.
## **Leveling my bed and managing with the screen**
For today I am going to level my bed, there are three springs under my bed which holds it. I put my nozzel above each one of the springs and leveld it by using an A4 paper, it will be easier to see how high your nozzle is. Before doing this, I tried to print a voron cube but failed as the nozzle hit the bed for some parts and beign to high for others. I bought the offical screen for Voron0 and wanted to use it. I tried to find different configuration manuals but they were not the same as mine, I bought mine from BigTreeTech, when I wnet onto their official Github page, I could't find any reference files for it as they haven't put any yet. Because I couldn't find any files and I am not really into using it very often, I decided not to use it for this printer, maybe there can be other uses for it.
## **Trying out the printer and sealing the printer**
Today I tried out my printer by letting it print a mini version, 50% size, of 3Dbenchy and Voron cube. The results are pretty good, so I decided to seal up my printer as it can both prevent ash from falling into it and reduce the noise, so I am finished with this printer!