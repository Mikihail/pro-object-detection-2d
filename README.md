
# Pro-Object-Detection-2D
This source code facilitates object detection in 2D and establishes the position in 3D coordinates of the detected objects based on RealSense D435 camera under ROS platform. It uses the HSV algorithm to filter a single color from the camera stream for object detection. If you have further advice or suggestions, please send an email to your new owner: Mikihail@gmail.com. This project is open for discussions and further developments.

## Steps to use this code:
- `$ catkin_make`
- `$ roslaunch realsense2_camera rs_rgbd.launch`
- `$rosrun opencv_object_tracking object_filter`