# SCARA-52900
Work-in-progress for integrating aliexpress chinese pvc SCARA Robotic Arm Model 52900 with ROS. 
Test its joints:  roslaunch urdf_tutorial display.launch model:=urdf/scara_52900.urdf.xacro

Gazebo test: 

cd into src/scara_52900

start gazebo client in another terminal after sourcing . ~/catkin_ws/devel/setup.bash

roslaunch scara_52900 all.launch

to move various joint, try rostopic pub /scara_52900_waist_controller/command std_msgs/Float64 "data: -2.107" with different data values. Sub "waist" for "elbow" "shoulder" "wrist" to move different joints.
