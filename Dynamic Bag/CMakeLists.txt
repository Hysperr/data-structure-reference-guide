cmake_minimum_required(VERSION 3.7)
project(Dynamic_Array)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp bag.cpp bag.h)
add_executable(Dynamic_Array ${SOURCE_FILES})