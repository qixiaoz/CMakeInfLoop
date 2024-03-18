cmake_minimum_required(VERSION 3.21)
project(hello)

set(CMAKE_CXX_COMPILER "/usr/bin/clang++")

add_library(${PROJECT_NAME} MODULE hello.cpp)

install(
    TARGETS ${PROJECT_NAME} LIBRARY DESTINATION hello
)