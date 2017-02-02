cmake_minimum_required(VERSION 3.6)
project(alp_p)

set(CMAKE_C_STANDARD 99)

set(SOURCE_FILES arglist.c)
add_executable(alp_p ${SOURCE_FILES})