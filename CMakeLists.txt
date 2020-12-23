cmake_minimum_required(VERSION 3.10)

# The value of this variable should be set prior to the first project()
set(CMAKE_OSX_DEPLOYMENT_TARGET "10.9" CACHE STRING "" FORCE)

# set the project name and version
project(gsplus VERSION 0.15)

add_subdirectory(src)
