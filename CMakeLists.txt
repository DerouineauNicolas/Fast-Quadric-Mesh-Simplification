cmake_minimum_required (VERSION 2.6)
project (QuadraticMeshSimplification)
# The version number.
set (Tutorial_VERSION_MAJOR 1)
set (Tutorial_VERSION_MINOR 0)
 
include_directories(${PROJECT_SOURCE_DIR}/src.cmd/)
 
# add the executable
add_executable(FQMS "${PROJECT_SOURCE_DIR}/src.cmd/Main.cpp")

install(TARGETS FQMS DESTINATION /usr/local/bin/)