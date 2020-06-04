# universalRobotRL

ROS melodic, ubuntu 18

To launch files, download the universal robot files here: 
https://github.com/UniversalRobots/Universal_Robots_ROS_Driver


To launch the environment: 

1. Bring up the gazebo simulation environment
$ roslaunch ur_gazebo ur5.launch

2. Start planing execution
$ roslaunch ur5_moveit_config ur5_moveit_planning_execution.launch sim:=true

