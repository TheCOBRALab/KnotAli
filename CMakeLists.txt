project(knotAli)

cmake_minimum_required(VERSION 3.8)
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

set( CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} \ -O3 -g" )


add_subdirectory(src)
