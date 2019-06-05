cmake_minimum_required(VERSION 2.8.3)
project(sawyer_robotiq)

find_package(catkin REQUIRED COMPONENTS
)

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES sawyer_robotiq
#  CATKIN_DEPENDS intera_interface robotiq_c_model_viz
#  DEPENDS system_lib
)

include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)
