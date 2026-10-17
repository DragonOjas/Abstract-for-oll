# RoboRacer
**Design Abstract** – Round 1 Online Submission
Team Name and Team ID: **[RoboRush]** and    **[TM-76ACFF84EC6]** respectively.

**Team Members:**
1.	[Shantanu Sharma and OLLR-0E9EDD4AA714 (Team Leader)
2.	[Ojas Kumar and OLLR-A8700D9BF566]
3.	[Jonathan William Cooper and OLLR-BE288DD2BF20]
4.	
**Track: RoboRace**


# Technical overview
In this robot we have worked to maximize the speed while still having decent control, we have tried our best to maximize both the aspects as both are dependant on each other if one is overpowered the other one fails miserably, and vice versa.  In our model our main goal was to keep both decently good in parallel.

# Introduction to our bot, Ignis Aura
We have choosen this name as it shows both the aspect of our bot which are the aura and the ignis meaning the fire it will posses. We have the bot which will light the entire track on fire and do its best to win. This bot is our first big innovation together as a team. If we were to combine the total group hours of the work, it would definately add up to atleast a minimum of 40 entire hours.

# Problems faced by us
Such a thing or anything good at all cannot exist without problems and faults, and our project was the peak example for this, we had so massive of downfalls. When we initially started the work it worked seamlessly, we were using witpro blox, and he next day it suddenly stopped working then we got to know that the block has been fried taking this as our first setback we started the work again and this happened more and more times then we got to know that these weren't even allowed at all. It was at this moment we bought an actual esp devkit board we had to do some changes in the code to make it shift from esp 12E->32 devkit v1. And thinking good will happen we fried another one of our expensive chip. We were so set back and got off the guard that we thought this is the end and then we asked our teachers to help us, are school teachers were quite helpful in all this and our esp finally started working the code finally worked. Our school teachers were quite helpful with the overall code and wifi integration but we needed external help for the hardware so we reached out to the oll team from Lucknow and then Farhan sir helped us quite a bit and also connected us to other trainers which helped us. At the end our bot finally started working and our esp wasn't heating, the main problem was in our motor driver. Seeing the cost of esp it has fried we literally wanted to burn that motor driver in open fire. (we didn't actually did this for safety purposes)

# The hardware
The hardware which we used are listed below
1. Motor Driver
- It helped us in providing ample power to both the motors while making sure they don't explode and receive the signal well
2. Esp 32 Dev-Kit v1
- The main brain of our racecar, which helped us to make a server hosted directly on the esp which we connected with our phone for the controller, which gave us one of the best latency, approx 10-20ms.
3. Buck converter
- It helped us to power the esp while not frying it as we were giving it raw 12v power, the main work the buck converter served was to act like a fry protector and helped us to run the esp safely.
4. Pack of 3, of Li-ion battery
- We used 3 li-ion batteries to make sure we have ample of power to run all our components with a good maah.
5. 2 bega motors
- We used 2, 12v bega motors to run our racecar, we planned to use better motors but we were limited by the maximum volate limit so we kept it 12v to be on the safer side, the motors run seamlessly as we had the whole circuit in parallel, which provides with equal volatage throughout the circuit
6. A metal chasis
- Our chasis is of metal, it weighed approx 500gm which became around 600gn when we added the other components, we had to also attach a peice of paper on top of the chasis, and above the paper we had glue gun or cardboard attached to ensure no short circuit occurs due to the metal chasis
7. Wheel caster
- We used 2 tyre 1 wheel caster setup to ensure we don't go overweight and also maintain a good amount of handling while being on the safer side

# Coding Process
We have uploaded our code to [GitHub](https://github.com/DragonOjas/ROBORACER), this allowed for seamless access even without our devices, which means we can access it from anywhere. This code granted us with a dedicated server which was hosted directly on the esp providing ease of use while maintaining the limits esp had. Beside having the code as open source we made sure to use a different network name and password privately when we uploaded the code to Arduino ide to ensure that no one else can gain control over our robot.

# Conclusion
At last, after making this robot we were introduced to various things like how to even use an esp properly and how not to use it. We got to know better about the grounding, as our motors didn't actually work until we connected the ground of the driver to that of the esp. It brought us closer as a team and as friends, we spent countless hours working and tinkering with the bot, all three of us had one thing in common which was *raw passion* for the completion of the robot. And this *raw passion* drived us crazy far in order to complete this roboracer we did all we could in our reach to build this and this is where we stand.

**Thank you for reading the entire extract!**
**The source code of this particular file can be found on [here](https://github.com/DragonOjas/Abstract-for-oll/blob/jolever/README.md)** 
**We hope you liked our project! :)**
