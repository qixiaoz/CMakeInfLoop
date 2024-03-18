cmake_minimum_required(VERSION 3.21)

set(CMAKE_CXX_COMPILER "/usr/bin/clang++")

project(world)

add_library(${PROJECT_NAME} MODULE world.cpp)

install(
    TARGETS ${PROJECT_NAME} LIBRARY DESTINATION world
)