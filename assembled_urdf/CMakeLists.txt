cmake_minimum_required(VERSION 3.10.2)
project(assembled_urdf)
find_package(ament_cmake REQUIRED)

ament_package()

install(DIRECTORY config launch meshes urdf DESTINATION share/${PROJECT_NAME})
