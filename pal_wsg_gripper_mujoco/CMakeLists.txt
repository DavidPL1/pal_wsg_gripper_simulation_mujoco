cmake_minimum_required(VERSION 3.0.2)

project(pal_wsg_gripper_mujoco)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

find_package(catkin REQUIRED)

catkin_package(
)

install(DIRECTORY launch assets example #config
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
