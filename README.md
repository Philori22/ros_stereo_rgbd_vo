ros_stereo_rgbd_vo

An OpenCV based Implementation of Stereo and RGBD Visual Odometry for ROS. 

This repo will subscribe to a pair of image topics as well as a camera info topic to pull a calibrated camera's intrinsics and distortions for this algorithm to work.

It uses GFTT features for feature detection, and optical flow for feature matching.