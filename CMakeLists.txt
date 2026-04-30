cmake_minimum_required(VERSION 4.2)
project(fastlog)

set(CMAKE_CXX_STANDARD 23)

add_library(fastlog SHARED library.cpp)
