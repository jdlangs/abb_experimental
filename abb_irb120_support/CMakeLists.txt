cmake_minimum_required(VERSION 3.5)

project(abb_irb120_support)

# if (CATKIN_ENABLE_TESTING)
#   find_package(roslaunch REQUIRED)
#   roslaunch_add_file_check(tests/roslaunch_test.xml)
# endif()

install(DIRECTORY config launch meshes urdf
  DESTINATION share/${PROJECT_NAME})
