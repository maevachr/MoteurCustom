cmake_minimum_required(VERSION 3.10)
project(MoteurCustom)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -std=c++17")
set(MY_SOURCE_DIR src/)
include_directories(${MY_SOURCE_DIR})

set(SOURCES_FILES src/main.cpp)

add_executable(moteurCustom ${SOURCES_FILES})
