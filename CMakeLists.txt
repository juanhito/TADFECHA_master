cmake_minimum_required(VERSION 3.14)
project(TADFECHA_master)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(TADFECHA_master
        Fecha.cpp
        Fecha.h
        main.cpp)
