# basic-imu-filtering
This package uses robot_localization to process data from single IMU like `SEN0386` published in `/imu` topic.  
## Installation 
After cloning this repo into your `/src` path of your ROS workspace, install required packages by:  
### Using rosdep
```
rosdep install -r --from-paths src
```
### Manually
If, for some reason, rosdep could not reach required packages, you can install them by:  
```
sudo apt install ros-$ROS_DISTRO-robot-localization
```
