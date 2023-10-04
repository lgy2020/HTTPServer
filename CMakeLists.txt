cmake_minimum_required(VERSION 3.0)

project(HTTPSERVER)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -g -O2 -Wall")

include_directories()

add_executable(main main.cpp)