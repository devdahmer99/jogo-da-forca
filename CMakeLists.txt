cmake_minimum_required(VERSION 3.21)
project(jogo_da_forca)

set(CMAKE_CXX_STANDARD 14)
add_definitions(-std=c++11)

include_directories(.)

add_executable(jogo_da_forca
        forca.cpp)
