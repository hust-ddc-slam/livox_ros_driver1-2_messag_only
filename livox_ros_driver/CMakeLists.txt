cmake_minimum_required(VERSION 3.0)
project(livox_ros_driver)

find_package(catkin REQUIRED COMPONENTS
  roscpp
  rospy
  sensor_msgs
  std_msgs
  message_generation
)

add_message_files(FILES
  CustomPoint.msg
  CustomMsg.msg
)  

generate_messages(DEPENDENCIES
  std_msgs
)
