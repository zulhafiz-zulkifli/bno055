cmake_minimum_required(VERSION 2.8.3)
project(bno055)

find_package(catkin REQUIRED COMPONENTS
  rospy
  sensor_msgs
  std_srvs
)

catkin_python_setup()

catkin_package(
   CATKIN_DEPENDS rospy sensor_msgs
)

include_directories(
  ${catkin_INCLUDE_DIRS}
)

