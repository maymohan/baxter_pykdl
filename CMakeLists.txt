cmake_minimum_required(VERSION 3.0.2)
project(baxter_pykdl)

find_package(catkin
  REQUIRED
  COMPONENTS
  rospy
  geometry_msgs
  sensor_msgs
  tf
  baxter_core_msgs
  baxter_interface
)

catkin_python_setup()

# urdfdom needs to be added this way since it does not support generators
# set(libraries "urdf;/usr/lib/liburdfdom_sensor.so;/usr/lib/liburdfdom_model_state.so;/usr/lib/liburdfdom_model.so;/usr/lib/liburdfdom_world.so;/usr/lib/libconsole_bridge.so.1.0;/usr/lib/libboost_thread.so.1.76.0;/usr/lib/libtinyxml.so;/usr/lib/libtinyxml2.so")

catkin_package(
  CATKIN_DEPENDS
  rospy
  geometry_msgs
  sensor_msgs
  urdfdom
  tf
  baxter_interface
  baxter_core_msgs
  # DEPENDS
  # python_orocos_kdl
  # libraries
)

install(
  DIRECTORY scripts/
  DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION}
  USE_SOURCE_PERMISSIONS
)
