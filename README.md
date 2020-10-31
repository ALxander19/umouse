# umouse
Micro mouse robot with a maze

Put the maze folder in the following directory:

/home/user/.gazebo/models/

To see the hidden directory (.gazebo) press Ctrl + H

Open the robot using the ROS Visualizator -> RVIZ

```
roslaunch umouse_description rviz.launch
```

Open the robot in Gazebo in a empty space:

```
roslaunch umouse_description spawn_robot.launch
```

Open the robot in Gazebo with a maze:

```
roslaunch umouse_gazebo spawn_robot.launch
```
