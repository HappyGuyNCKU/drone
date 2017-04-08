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



2. Install required image_pipeline packages

```
$ sudo apt-get install ros-DITRO-image_view
$ sudo apt-get install ros-DITRO-camera_calibration
$ sudo apt-get install ros-DITRO-stereo_image_proc
```

3. Camera test





The final performance is 0.5 fps.
