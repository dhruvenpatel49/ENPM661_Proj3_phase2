# ENPM661_Proj3_phase2
Planning Project - A* algorithm on turtlebot 

Team mates - Kaustubh Bhatt & Dhruven Patel

Github link: https://github.com/dhruvenpatel49/ENPM661_Proj3_phase2.git
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

Open two terminals and in the first terminal run the below code: -

  cd ~/catkin_ws && catkin_make

  roslaunch turtlebot3_gazebo turtlebot3_world.launch

In the second terminal run the below code:-


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
Enter goal X co-ordinates: 400
Enter goal Y co-ordinates: 25

Link to the video result for test case 1 is : https://drive.google.com/file/d/1kbQ_sMC8OusOAWHpwqbVfmNADwfSobaC/view?usp=share_link

Link to the video result for test case 2 is : https://drive.google.com/file/d/1CmNnqs-0UKg_tclKM9T6stQi4fiHCj_T/view?usp=share_link

Link to the part 1 test case: https://drive.google.com/file/d/1xRW3ODQ0w2HCTlabJtrkY0yGznjJ-j60/view?usp=drive_web

