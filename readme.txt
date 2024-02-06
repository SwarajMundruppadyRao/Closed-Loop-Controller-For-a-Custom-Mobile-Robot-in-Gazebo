Steps to follow to run the package:

1.--------------------------------------------  
Unzip the package and paste it in the desired workspace folder

2.--------------------------------------------  
Build the package and source

3.--------------------------------------------  
To launch the robot use the launch files located in the root directory of the ugv folder

4.-------------------------------------------- 
To run teleop controller : Set the orientation in spawn file , then launch the robot model in the gazebo world and run the following command ros2 run teleop_control control

5.-------------------------------------------- 
To run publisher and subscriber for only yaw controller : Set the orientation in spawn file , then launch the robot model in the gazebo world and run the following command : ros2 run closedloop_control control and to run subscriber, run the following command in another terminal: ros2 run subscriber control

6.-------------------------------------------- 
To run publisher and subscriber for yaw and position controller : Set the orientation in spawn file , then launch the robot model in the gazebo world and run the following command : ros2 run new_closedloop_control control and to run subscriber, run the following command in another terminal: ros2 run subscriber control
