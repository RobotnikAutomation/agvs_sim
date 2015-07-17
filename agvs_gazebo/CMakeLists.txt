cmake_minimum_required(VERSION 2.8.3)
project(agvs_gazebo)

## Find catkin macros and libraries
## if COMPONENTS list like find_package(catkin REQUIRED COMPONENTS xyz)
## is used, also find other catkin packages
find_package(catkin REQUIRED COMPONENTS
  agvs_description
  gazebo_ros
  roscpp
  std_msgs
  std_srvs
  tf
  joint_state_controller
  velocity_controllers
  effort_controllers
)

catkin_package()
