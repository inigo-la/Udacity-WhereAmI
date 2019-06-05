# Udacity-WhereAmI
## Udacity Robotics Software Engineer Nanodegree Program Project 4: Where Am I

A mobile robot that localizes itself using ROS AMCL (Adaptive Monte Carlo Localization) package.


It is composed of 1 ROS package:
* my_robot

Includes cfg files for rviz, world map files and launch scripts.


### How to build project

Copy my_robot directory to a working catkin workspace src directory and build with catkin_build.


### How to run project

To launch de simulation, execute in a terminal:
```bash
$ cd <catkin_workspace_dir>
$ roslaunch my_robot world_amcl.launch
```

To run AMCL:
```bash
$ cd <catkin_workspace_dir>
$ roslaunch my_robot amcl.launch
```

Now you can send navigation goals in rviz and the robot will eventually localize itself.
