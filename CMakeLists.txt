cmake_minimum_required(VERSION 3.21)

project(helloworld)

add_subdirectory(hello)
add_subdirectory(world)

add_dependencies(hello world)