
This repository contains the code of our eYantra project, a robotics competition organized by IIT Bombay.  

Theme of the Project:
Navigate a Terrain was our theme. For our project, The Terrain was a Region consisting of five concentric rings.
In the middle of the Region in the Base Station was a “Spotter” that provides guidance to the “Rover”, the robot moving through the Terrain.
A Map of the Terrain was provided indicating the Checkpoints along the path to the Base Station.
Checkpoints ensured accurate tracking of the Spotter by the Rover as it navigatedd through the concentric rings having openings at random
points. The Challenge in this theme was to design and program two independent robotic systems that can communicate with each other
in order to navigate the spaces between the rings of the arena without missing the Checkpoints.
The challenge was to navigate the terrain in the shortest time possible and reach the Base Station.

A brief description on the two autonomous systems, the rover and the base station:

Tasks Performed by Rover:
1. Rover traverses from one ring to other using Openings in the Ring.
2. Rover identifies the color of each Checkpoint and glows the RGB LED on the Rover. 
3. Rover sends the information related to the identified color to the Base Station. 
4. Base Station glows a RGB LED of the identified color. 

