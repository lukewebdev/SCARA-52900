# SCARA-52900
Work-in-progress for integrating aliexpress chinese pvc SCARA Robotic Arm Model 52900 with ROS. 
Test its joints:  roslaunch urdf_tutorial display.launch model:=urdf/scara_52900.urdf.xacro

Gazebo test (not working): cd into src/scara_52900

roslaunch scara_52900 joints.launch

currently SCARA arm shows up on its side in Gazebo.
