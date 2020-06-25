# Universal Robot Reinforcement Learning

**ROS melodic, ubuntu 18**

To launch files, download the universal robot files [here](https://github.com/UniversalRobots/Universal_Robots_ROS_Driver)

(when launching, we are going to limit the rotation of the motors to pi instead of 2pi)

## Launch the Environment:

in the terminal: 
```
$ roslaunch ur_gazebo ur5.launch limited:=true
$ roslaunch ur5_moveit_config ur5_moveit_planning_execution.launch sim:=true limited:=true
$ roslaunch ur5_moveit_config moveit_rviz.launch config:=true
```
