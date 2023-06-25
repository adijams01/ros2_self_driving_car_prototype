# Self Driving Car Prototype
#### 1:8 Scaled autonomous vehicle with ackerman drive




<img width="960" alt="Screenshot 2023-06-25 234154" src="https://github.com/adijams01/ros2_self_driving_car_prototype/assets/92617405/66a4c34e-ed83-422d-91cd-6839d52eb2a3">

## Issues
* ackerman Gazebo pluggin
* steering wheel joints (not spawning in Gazebo)

## Regular Commands
```
colcon build --symlink-install
```
```
source install/setup.bash
```
```
source /opt/ros/foxy/setup.bash
```
```
ros2 launch my_bot rsp.launch.py
```
```
rviz2
```
```
ros2 run joint_state_publisher_gui joint_state_publisher_gui
```
```
ros2 launch my_bot launch_sim.launch.py
```
```
ros2 run teleop_twist_keyboard teleop_twist_keyboard
```
```
ros2 run teleop_twist_keyboard teleop_twist_keyboard --ros-args -r /cmd_vel:=/diff_cont/cmd_vel_unstamped
```

