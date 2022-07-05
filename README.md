# Maze-solver-using-arduino- 
# This is the source code we have used in our model


Have you ever wondered how Tesla is able to create a fully functioning autonomous car? In this article, we will be going to see one of the building blocks of autonomous vehicles which is detecting obstacles and taking action according to that.

What does this article consist of ?

This article consists of two different phases: First phase is the developing phase where you will be able to understand how Johnny is made from scratch & its working and the second phase is my experience in TECHMITI'22 and getting into top 3 in Bot-A-Maze event.

Let’s start with the first phase- The Developing Phase.

/**Introduction**/


In order to automate our daily tasks, modern robotics technologies are primarily concerned with creating self-navigating autonomous robots.

The maze solving robot — also known as a micro mouse (we called it Johnny) — is designed to find a path without any assistance or help. It is one of the building blocks for making autonomous vehicles that must figure out the way on its own in order to effectively navigate the maze.

Building Johnny from Scratch


Components which are used to build Johnny:

4 TT geared motor
4 Wheels 
3 Ultrasonic sensor module
Arduino UNO with cable
L298N Motor driver
Two/four wheel robot chassis
Switch
Jumper cables
Pair of 18650 Lithium-ion rechargeable battery(Rating 3.7V, 2000A)
Figure shows the components used    



Steps to build Johnny:
First, we will fix all the four motors on the chassis board with hot glue and connect the same side of motors in parallel connection. 
We will now fix the Arduino UNO and L298N motor driver on the chassis with the help of screws and nuts. 
Take three metal strips for the support to the sensors and fix them. 
Place the sensor modules on metal strips with double sided tape and align the sensors at 120 degree with each other. 

And this is where our assembling of parts has been completed. Now let's move on to wiring connections:





Connect the left motors with output 1 & output 2 and right motors with output 3 & output 4 of the motor driver (the same side of motors should rotate in the same direction). 

Lastly, we upload the arduino code to make Johnny autonomous. 

Our Johnny is ready! Now it's time to participate in the tech fest TECHMITI’22.



That begins the second phase of this article- My experience in the TECHMITI’22 and getting into the top3.

DAY 1

This is my first tech fest in this college, all thanks to the pandemic. The joy of being together, meeting people and representing our college at the state level always increases dopamine level and I was in that state. I reached the fest location early in the morning on the day 1 and I was amazed to see the level of decoration and preparation for each event, literally that was insane. 


The Bot-A-Maze event was in 4 hours after I reached the location, and then I had to assemble the Johnny and test it multiple times in order to win the event. So, I immediately started working on Johnny. Afterwards everything was working and then we went to the event hall.

Everyone in the hall is looking very confident, some people have autonomous robots and some of them are remote controlled and they were testing their models. The maze looks very difficult and has very narrow paths, this makes the competition very tough.

Now, the event has started, two college group’s models already gave tough competition to each other, but somehow the left ultrasonic sensor of Johnny started giving unwanted readings which led to incorrect decisions for automation of the Johnny. 

After some time I thought we fixed the problem and we took it to the competition and within 2 minutes it reached the last section of the maze and again the left sensor started to give undesirable readings and there I thought we lost the competition. But somehow Johnny solved the maze in 9 minutes which was not better than the other two models which performed before me. I lost all the hope for winning this tournament. 

So, without seeing the end result I moved out from the hall and I started working on another event which was line follower. But again somehow, I broke one of the IR sensors of the model and now the model does not work. 

DAY 2  

The result day, I had no idea that I won the third prize in the Bot-A-Maze. And then, an announcement happened where they called my name against the third prize, and they appreciated Johnny for reaching the last section of the maze within 2 minutes. This is the fastest robot to reach the last section. 







Co-owner- Vishal Kumar

