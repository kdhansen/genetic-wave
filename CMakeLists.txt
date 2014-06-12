cmake_minimum_required(VERSION 2.8.9) 
project(genetic-wave)

include_directories(include)

add_executable(${CMAKE_PROJECT_NAME}
    ${CMAKE_SOURCE_DIR}/src/main.cpp
    ${CMAKE_SOURCE_DIR}/src/genetic-algorithm.cpp
    ${CMAKE_SOURCE_DIR}/src/performance-function.cpp
) 