cmake_minimum_required(VERSION 3.8)
project(inf2ccsass2)

set(CMAKE_C_STANDARD 99)

set(SOURCE_FILES mem_sim.c)
add_executable(inf2ccsass2 ${SOURCE_FILES})