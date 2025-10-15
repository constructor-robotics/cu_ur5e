cmake_minimum_required(VERSION 3.0.2)
project(cu_ur5e_description)

find_package(catkin REQUIRED)

catkin_package()

install(DIRECTORY config launch robots urdf
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
