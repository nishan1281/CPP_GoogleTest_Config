cmake_minimum_required(VERSION 3.28)
project(try)

set(CMAKE_CXX_STANDARD 17)

add_executable(try main.cpp
        cmake-build-debug/sdf.cpp
        aadf.cpp)
