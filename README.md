# SCARA-52900
Work-in-progress for integrating aliexpress chinese pvc SCARA Robotic Arm Model 52900 with ROS. 
Test its joints:  roslaunch urdf_tutorial display.launch model:=urdf/scara_52900.urdf.xacro

Gazebo test (not working): cd into src/scara_52900



start gazebo client in another terminal after sourcing . ~/catkin_ws/devel/setup.bash

roslaunch scara_52900 gazebo.launch

currently SCARA arm shows up on its side in Gazebo.
