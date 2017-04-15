cmake_minimum_required(VERSION 3.7)
project(Horse)

set(CMAKE_C_STANDARD 99)

set(SOURCE_FILES Horse.c)
add_executable(Horse ${SOURCE_FILES})