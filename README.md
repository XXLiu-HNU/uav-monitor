# UAV-Monitor

This is a tool to detect the status of the drone through the terminal, eliminating the step of `rostopic echo xxx`. Try to subscribe to the topic of your interest by reading [FTXUI](https://github.com/ArthurSonzogni/FTXUI)

<img src="https://github.com/user-attachments/assets/99abd26d-ba97-4fdd-9e58-1f276fb70bf8" alt="image_00000" width="600"/>

## How to use

```
git  clone https://github.com/XXLiu-HNU/uav-monitor.git
cd uav-monitor
catkin_make
#This step requires an internet connection and patience
source devel/setup.bash
roslaunch ftxui_ros single_start.launch 
```

And you can change the topic in `single_start.launch ` to match the corresponding topic.
