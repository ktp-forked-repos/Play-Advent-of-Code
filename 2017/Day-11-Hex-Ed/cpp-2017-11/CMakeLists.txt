cmake_minimum_required(VERSION 3.5)
project(cpp_2017_11)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main_part_2.cpp)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR})
add_executable(cpp_2017_11 ${SOURCE_FILES})