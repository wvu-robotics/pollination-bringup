# simulator-pollination-combined
Combine bramblebee arm and base together
## Launch
Launch in following order:
```
roslaunch combined greenhouse.launch
roslaunch nav_filter test_online.launch
roslaunch comnined combined_viz.launch
//Other Extra controllers used by code, such as
roslaunch bramblebee_navigation move_base_mapless_demo.launch
rosrun manipulation_control ee_go_to_pose
//more pollination state machines/classifiers
```
## Dependencies
Relies on:
simulator-pollination-bramblebee
simulator-pollination-manipulator
simulator-pollination-greenhouse
simulator-slam
