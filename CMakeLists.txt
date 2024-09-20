cmake_minimum_required(VERSION 3.10)

project(hello VERSION 1.0)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

add_executable(hello src/main.c)
#target_link_libraries(hello)
