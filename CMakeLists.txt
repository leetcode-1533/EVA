cmake_minimum_required(VERSION 3.9)
project(EVA)

set(CMAKE_CXX_STANDARD 11)

add_executable(EVA main.cpp)
add_executable(Proxy src/proxy.cpp src/proxy.h)