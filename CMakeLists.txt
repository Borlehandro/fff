cmake_minimum_required(VERSION 3.17)
project(fff)

set(CMAKE_CXX_STANDARD 14)

add_executable(fff main.cpp Entity.h ParticularEntity.cpp ParticularEntity.h EntityFactory.h EntityFactory.cpp)