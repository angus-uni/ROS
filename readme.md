
# ROS cheatsheet

1. [Linux Commands](#Some-Useful-Linux-Commands)
2. [Sheff Commands](#Sheff-Commands)
3. [Core Commands](#Core-commands)
4. [Rostopic](#Rostopic)


## Some Useful Linux Commands

| Name | Command |
| --- | ----------- |
| Create a new file | ``` touch [filename.extension] ``` |
| Make file executable | ``` chmod +x [filename.extension] ``` |
| Display file content in shell | ``` cat [filename.extension] ``` |
| Print working directory | ``` pwd ``` |
| Create new directory | ``` mkdir [directory_name] ``` |

## Sheff Commands

1. [Restore saved work](#Restore-saved-work)
2. [Backup work](#Backup-work)


#### Restore saved work

```shell
rosrestore.sh
```

#### Backup work

```shell
rosbackup.sh
```

## Core Commands

1. [Launch Simulation](#Launch-Simulation)
2. [Launch Keyboard Listener](#Launch-Keyboard-Listener)
3. [Run a package](#Run-a-package)
4. [Create a package](#Create-a-package)
5. [Navigate to ROS package](#Navigate-to-ROS-package)
6. [Launch the ROS master](#Launch-the-ROS-master)


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
#### Navigate to ROS package

```shell
roscd [package_name]
```

#### Launch the ROS master

```shell
roscore
```

## Rostopic

1. [View all active ROS nodes](#View-all-active-ROS-topics)
2. [View info about a ROS topic](#View-info-about-a-ROS-topic)


#### View all active ROS topics

```shell
rostopic list
```

#### View info about a ROS topic

```shell
rostopic info [topic_name]
```

