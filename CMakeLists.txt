cmake_minimum_required(VERSION 3.0.2)
project(peyk_auto_reboot)

## Compile as C++11, supported in ROS Kinetic and newer
# add_compile_options(-std=c++11)

## Find catkin macros and libraries
## if COMPONENTS list like find_package(catkin REQUIRED COMPONENTS xyz)
## is used, also find other catkin packages
find_package(catkin REQUIRED COMPONENTS
  rospy
  std_msgs
  sensor_msgs
)

catkin_package(

)

include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)
