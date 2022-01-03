cmake_minimum_required(VERSION 3.19)
project(CacheInspector)

set(CMAKE_CXX_STANDARD 14)

add_executable(CacheInspector main.cpp)
add_executable(CacheInspector-assoc testAssociativity.cpp)