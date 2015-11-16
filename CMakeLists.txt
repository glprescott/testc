cmake_minimum_required(VERSION 3.3)
project(testc)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES hello.c)
add_executable(testc ${SOURCE_FILES})