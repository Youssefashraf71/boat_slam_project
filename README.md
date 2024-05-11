# boat_slam_project
Boat Project with SLAM and Obstacle Avoidance


## Run The Visualization

```
cd ~/Desktop/boat_slam_project/
source devel/setup.bash

roslaunch boat_launcher master_w1.launch 
or
roslaunch boat_launcher master_w2.launch 



```

## Control the boat using keyboard

```
cd ~/Desktop/boat_slam_project/
source devel/setup.bash


roslaunch boat_launcher keyboard_control.launch 

```

## Start Obstacle Detection

```
cd ~/Desktop/boat_slam_project/
source devel/setup.bash
roslaunch boat_launcher hector_slam.launch 

```

## Create Map

```
cd ~/Desktop/boat_slam_project/
source devel/setup.bash
roslaunch hector_slam_launch boat_slam.launch 


```

