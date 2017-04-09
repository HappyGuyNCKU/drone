# ROS Depth Map Generator

This Depth Map Generator is based on ROS package.<br/>
Producing Depth Map with ROS nodelet which reduce the data transfer time.<br/>
Test environment is Raspberry Pi 3.<br/>


## Prerequisite

1. Install ROS 

Install ROS framework from http://www.ros.org/install/.<br/>
DISTRO Indigo and kinetic is tested and recommanded on this project.<br/>
Bare version is enough to proceed.<br/>

2. Setup Workspace

Setting up the ROS environment on the computer following  http://wiki.ros.org/ROS/Tutorials/InstallingandConfiguringROSEnvironment

ps.Inside the tutorial use catkin_make ultility.But we used to use catkin tools,which provides much more feature and easy to use.
To install catkin tools
```
sudo apt-get install python-catkin-tools
```

3. Setup camera node

```
$ cd $CATKIN_WS/src
$ git clone https://github.com/ktossell/camera_umd

# jpeg_streamer package is useless to us.Put it into blacklist
$ catkin config --blacklist  jpeg_streamer

# build workspace
$ catkin build

# Test

```


2. Install required image_pipeline packages

```
$ sudo apt-get install ros-DITRO-image_view
$ sudo apt-get install ros-DITRO-camera_calibration
$ sudo apt-get install ros-DITRO-stereo_image_proc
```

3. Camera test





The final performance is 0.5 fps.
