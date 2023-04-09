# ENPM661_Proj3_phase2
Planning Project - A* algorithm on turtlebot 

Team mates - Kaustubh Bhatt & Dhruven Patel

Github link: 
------------------------------------------------------------------------------------------------------------------------------------------
Libraries Used are mentioned below

numpy
math
matplotlib
time
heapq
dist

------------------------------------------------------------------------------------------------------------------------------------------
There are 3 files to this package

1) The sorce code file names as "turtlebot_controller.py".
2) Launch the file "turtlebot3_world.launch which exists in turtlebot3_gazebo package.
3) The world file provided, named "map.world", which should be in the worlds folder in turtlebot3_gazebo.

Open two terminals and in the first terminal run the below code

cd ~/catkin_ws && catkin_make

source ~/.bashrc

roslaunch turtlebot3_gazebo turtlebot3_world.launch

In the second terminal run the below code

source ~/.bashrc

rosrun turtlebot3_gazebo turtlebot_controller.py


Then the code will ask for user inputs mentioned below:

Test Case 1

Enter clearance of robot: 10
Enter Low RPM:5
Enter High RPM: 9
Enter starting X co-ordinate: 50
Enter starting Y co-ordinate: 100
Enter Orientation of the robot at start node: 0
Enter goal X co-ordinates: 550
Enter goal Y co-ordinates: 20

Test Case 2

Enter clearance of robot: 10
Enter Low RPM: 5
Enter High RPM: 9
Enter starting X co-ordinate: 50
Enter starting Y co-ordinate: 100
Enter Orientation of the robot at start node: 0
Enter goal X co-ordinates: 500
Enter goal Y co-ordinates: 40

Link to the video result for test case 1 is : https://drive.google.com/file/d/1kbQ_sMC8OusOAWHpwqbVfmNADwfSobaC/view?usp=share_link

Link to the video result for test case 2 is : 



