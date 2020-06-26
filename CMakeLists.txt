cmake_minimum_required(VERSION 3.0)

project(hw2)

include_directories(test/)

file(GLOB SOURCES src/*.cpp)

add_executable(main ${SOURCES})






