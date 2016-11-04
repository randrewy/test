cmake_minimum_required(VERSION 2.8.7)

project(Test)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -std=c++14")

add_executable(main main.cpp)