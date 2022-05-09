cmake_minimum_required(VERSION 3.0.2)
project(robile_ros_navigation)

find_package(catkin REQUIRED COMPONENTS
  roscpp
  rospy
  std_msgs
  tf
)

catkin_package()
