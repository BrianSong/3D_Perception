# RoboND_3D_Perception
*In this project, A PR2 robot outfitted with an RGB-D camera is given a cluttered tabletop scenario where a perception pipeline using Filtering, Segmentation, Clustering and Object Recognition is used to identify target objects from a so-called “Pick-List” in a particular order, pick up those objects and place them in corresponding dropboxes.*

**Gazebo, RViz, Moveit!** are used for simulating the environment in this project and **Python with ROS** is choosed for implementing this project.

This is a `README` that includes all the key points and how I addressed each one.

**Steps to complete the project:**  


1. Make sure you have already setup your ROS Workspace in the VM provided by Udacity or on your own local Linux/ROS install.
2. Complete Perception Exercises 1, 2 and 3, which comprise the project perception pipeline.
3. Download or clone the project [repository](https://github.com/udacity/RoboND-Perception-Project).

# 1. Exercise 1, 2 and 3 pipeline implemented 
## 1.1 Complete Exercise 1 steps. Pipeline for filtering and RANSAC plane fitting implemented.
In this project, totoally 3 fitlers are used for filtering:
1. Statistical Outlier Filtering: The given initial cloud point is filled with noise as shown below:
![Initial_Point_Cloud_with_Noise](image/Initial_Point_Cloud_with_Noise.png)
2. Voxel Grid Downsampling:
3. PassThrough Filter:
