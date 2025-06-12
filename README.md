# CSCI-4360-5360-Homework-3-solution

Download Here: [CSCI 4360/5360 Homework 3 solution](https://jarviscodinghub.com/assignment/csci-4360-5360-homework-3-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

This is a programming assignment. Given a robot equipped with 6 Infrared sensors as
shown in the picture below (θ1=45o
, θ2 = 30o
, θ3= -30o
, θ4=-45o
. θ5= -130o
, θ6=130o
), write a C++
program that computes the magnitude of drive and direction of turn of the robot movement based
on sensor readings.
The sensor readings for three consecutive time steps are given in a data file: readings.dat.
(You may download the data file from the course page). For each set of 6 sensor readings, your
program should output the turn direction and magnitude in the form: the robot should turn -25
degrees with a magnitude of 0.35).
Use linear magnitude profile for the potential fields implemented for the motor schema.
MAX_DISTANCE of the sensor is set to D =10 cm.
Name your program pfield.cpp. Your program should include comments for logically
related code segments. It should also have program heading at the beginning of the program
which includes information such as the name of the programmer, due date, description of this
program.
Programming requirements:
• Your program reads the data from a data file named “readings.dat”
• The program should include at least these 3 functions:
o The main function handles the main program logic:
1. loop til the end of the data file is reached
1.1 loop over the 6 sensors:
1.1.1 SENSE: get sensor information for the
1.1.2 ACT: use repulsive potential field to generate the
vector for movement
1.1.3 Add the vector onto the overall sum-of-vectors
1.2 Report direction of movement for the current readings
o A function implements the repulsive potential field
o A function that adds two vectors
IR1
IR2
IR5
IR3
IR4
IR6
front
back
2
To submit your program, log onto D2L, go to the course page, and submit the program to
the Dropbox named “Homework 3”. You may submit multiple times before the due time. All
versions of the programs will be kept in your account
readings.dat content:
5 25 20 28 25 2
5 6 4 8 28 25
4 5 20 28 8 12



