cmake_minimum_required(VERSION 2.8.3)
project(godel_robot_resources)

catkin_package()

install(DIRECTORY
  launch
  urdf
  meshes
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)