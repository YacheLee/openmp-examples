cmake_minimum_required(VERSION 3.6)
project(Matrix)

set(CMAKE_CXX_STANDARD 14)

set(SOURCE_FILES main.cpp)
add_executable(Matrix ${SOURCE_FILES})

# for openmp
set(CMAKE_CXX_COMPILER "/usr/local/bin/g++-4.9")
set(CMAKE_CXX_FLAGS "${CMAKE_C_FLAGS} -fopenmp")