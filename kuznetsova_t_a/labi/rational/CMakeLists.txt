cmake_minimum_required(VERSION 3.6)
project(rational)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    rational.cpp
    rational.h
    rational_test.cpp)

add_executable(complex ${SOURCE_FILES})