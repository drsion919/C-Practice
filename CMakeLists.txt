cmake_minimum_required(VERSION 3.5)

project(C-Practice)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES HelloWorld.c)

add_executable(HelloWorld ${SOURCE_FILES})