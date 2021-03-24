
# ROS cheatsheet

## Core Commands

#### Launch Simulation

```shell
roslaunch turtlebot3_gazebo turtlebot3_empty_world.launch
```

#### Launch Keyboard Listener

```shell
roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch
```

#### Run a package

```shell
roslaunch [package name] [launch file]
```

#### Create a package

```shell
cd ~/catkin_ws/src
```

```shell
catkin_create_pkg [package_name] [dependancy_1] [dependancy_2]
```

## Some Useful Linux Commands

#### Make a file executable

```shell
chmod +x [filename.extension]
```


