cmake_minimum_required(VERSION 3.6)
project(Mapping)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp BVG/BVG.cpp BVG/BVG.h Process/Allocation.cpp Process/Allocation.h)
add_executable(Mapping ${SOURCE_FILES})