cmake_minimum_required(VERSION 2.8.3)
project(visual_servoing)

## Compile as C++11, supported in ROS Kinetic and newer
# add_compile_options(-std=c++11)

find_package(catkin REQUIRED COMPONENTS
		roscpp
		rospy
		tf
		geometry_msgs
		nav_msgs
		ackermann_msgs
		sensor_msgs
		roslaunch
)

catkin_package(
		CATKIN_DEPENDS
		roscpp
		rospy
		tf
		geometry_msgs
		nav_msgs
		ackermann_msgs
		sensor_msgs
		roslaunch
)
