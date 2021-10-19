# cmake_minimum_required(VERSION <specify CMake version here>)
project(assignment)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(assignment
        anomaly_detection_util.cpp
        anomaly_detection_util.h
        MainTrain.cpp)
