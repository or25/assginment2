# assginment2 at Mini Project: Topics in Robotics

By Or Liebembuk - 318896485
Guy Landoy  - 209494541

At the folder project2 there is all the files needed, but in any case we added the turtlebot files as well.

How to run the project:

1. Open Terminal and run the gazebo simulator:
$ cd catkin-ws/
$ souce devel/setup.bash
$ rosluanch project2 turtlebot3_bgu_world.launch
That should start the simulator. Wait a little bit if it takes time.

2. Open another terminal. 
$cd catkin-ws/
$ source devel/setup.bash
$ rosrun project2 scan.py
That should start our program. It will prompt a menu to choose from 1-4.
1 is for our robot to move forward.
2 is for our robot to turn. After sending 2 it will ask for degrees to turn.
3 is for our robot to find if it sees some colored object and it's length from it. 
Pls use only "green"/"red"/"blue", these are the only colors we supported in our project
4 is for the robot to search for an object with a specified color.



