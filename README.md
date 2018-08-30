# Pathfinding-Robot
#This is a demonstration of my embedded systems project
#This robot is designed to be put in a maze (see video) and find a path from its starting point to the finish line.
#The thick black line is the finish lines. Several thinner black lines are in the maze as well, these tell the robot when to start/ stop sending data back to the host computer via Bluetooth. 
#The "demo" video shows the robots pathfinding capabilities. This was an early video of the hardware, later iterations had a cleaner design but used the same code. 
#2 ultrasonic distance sensors were used to detect the distance from the right wall and forward most wall. Reflectance sensors on the bottom on the robot were used to detect the black lines. A Bluesmurf module was used to send data and receive commands over Bluetooth. An Arduino M0 was used to control and interface all the components.
