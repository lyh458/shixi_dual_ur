cmake_minimum_required(VERSION 2.8.3)
project(dual_ur_description)


find_package(catkin REQUIRED COMPONENTS roscpp rospy
catkin_package()

#############
## Install ##
#############

install(DIRECTORY launch DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
install(DIRECTORY urdf DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
install(DIRECTORY meshes DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
