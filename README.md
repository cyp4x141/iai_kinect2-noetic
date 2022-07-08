# Kinect2 Ros driver for ROS-Noetic

> Note: install libfreenect2 first

## Environment

1. ROS version: ros-noetic 
2. OS :ubuntu20.04 
3. kernel: Linux 5.13.0-39-generic

## Build
1. run `$ rosdep install -y --from-paths ./src --ignore-src --rosdistro noetic` in workspace
2. run `$ catkin build`
3. check and give permission with `$ lsusb` and `$ sudo chmoe 666 /dev/bus/usb/0**/0**`
4. `$ source devel/setup.bash` and `$ roslaunch kinect2_bridge kinect2_test.launch`


