cmake_minimum_required(VERSION 3.19)
project(CacheInspector)

set(CMAKE_CXX_STANDARD 14)

add_executable(CacheInspector main.cpp)
add_executable(testSize anotherSize.cpp)
add_executable(getCacheSize getCacheSize.cpp)