cmake_minimum_required(VERSION 3.0.2)
project(robot_sim_control)

find_package(catkin REQUIRED COMPONENTS
  roscpp
  rospy
  std_msgs
  sensor_msgs
  controller_manager
  joint_state_controller
)

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES robot_sim_control
#  CATKIN_DEPENDS rospy std_msgs
#  DEPENDS system_lib
)
