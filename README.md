# kritesh-seeruttun-TP5

To visualize the robot in rviz, the following command is typed:
oem@CRH-B214-PC05:~/catkin_ws/ri_arm_description/urdf$ :roslaunch urdf_tutorial display.launch model:=robot.urdf

To launch the demo.launch file in the ri_arm_config package, he following command is typed:
oem@CRH-B214-PC05:~/catkin_ws$ roslaunch ri_arm_config demo.launch

There are two launchfiles one to launch the services which use forward kinematics and the other which uses inverse kinematics:
oem@CRH-B214-PC05:~/catkin_ws$:roslaunch ri_arm_control direct.launch

oem@CRH-B214-PC05:~/catkin_ws$:roslaunch ri_arm_control indirect.launch
