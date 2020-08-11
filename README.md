# Reachy description

This ROS package contains URDF and collada files to use the [Reachy](https://pollen-robotics.com) robot with ROS1 Noetic.

## Quickstart

Launch the following command in order to run RViz, visualize the robot and move the joints:
```
roslaunch reachy_description display.launch gui:=True
```

## TODO
* [ ] Center joints at the center of motor axes
  * Avoid manual editing: will invalidate inertias
  * Display tf frames and clean up overlaps
* [ ] Correct right/left arm symmetry
