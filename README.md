# virat_slam

Package for SLAM execution using gmapping

Usage
---

Launch world

```bash
roslaunch virat_gazebo virat_bounded_world.launch
```

Execute SLAM

```bash
roslaunch virat_slam virat_slam.launch
```

Launch teleop node

```bash
roslaunch virat_teleop virat_teleop_key.launch
```

Save map

```bash
rosrun map_server map_saver -f ~/bounded_world_map
```

Prerequisite
------------

```bash
sudo apt-get install ros-kinetic-navigation
```
