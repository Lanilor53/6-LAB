cmake_minimum_required(VERSION 3.14)
project(RPM-Labs)

set(CMAKE_CXX_STANDARD 14)

add_executable(RPM-Labs main.cpp Polygon.cpp Polygon.h Point.h Rectangle.cpp Rectangle.h Triangle.cpp Triangle.h)