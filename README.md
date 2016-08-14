freenect_stack
==============

Build status on Travis CI [![Build Status](https://travis-ci.org/ros-drivers/freenect_stack.svg?branch=master)](http://travis-ci.org/ros-drivers/freenect_stack)

libfreenect based ROS driver

Installation
==============
In your catkin workspace:
```
cd catkin_ws/src
git clone https://github.com/ros-drivers/freenect_stack.git
cd freenect_stack
git checkout jade
cd ..
git clone https://github.com/ros-drivers/rgbd_launch.git
```

Testing
==============
Run the launch file:
```
roslaunch freenect_launch freenect.launch
```
Open rviz:
```
rosrun rviz rviz
```
Set the frame, Click add>Camera and select an image topic!
