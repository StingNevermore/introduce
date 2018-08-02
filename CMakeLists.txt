cmake_minimum_required (VERSION 2.8)

project (introduce)

add_definitions(-std=c++11)
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

aux_source_directory (src SRCS)

add_executable(Introduce ${SRCS})
