cmake_minimum_required(VERSION 3.1)
project(stl_utils)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS}")

set(SOURCE_FILES main.cpp)
add_executable(stl_volume ${SOURCE_FILES})
