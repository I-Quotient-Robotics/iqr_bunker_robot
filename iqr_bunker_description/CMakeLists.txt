cmake_minimum_required(VERSION 3.0.2)
project(iqr_bunker_description)

find_package(catkin REQUIRED COMPONENTS
  urdf
  xacro
)

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES iqr_bunker_description
#  CATKIN_DEPENDS urdf xacro
#  DEPENDS system_lib
)

include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)
