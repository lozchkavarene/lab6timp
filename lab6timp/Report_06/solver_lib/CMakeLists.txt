cmake_minimum_required(VERSION 3.12)

project(solver_lib)

set(SOURCE_FILE solver.cpp)
set(HEADER_FILE solver.h)

add_library(solver_lib STATIC ${HEADER_FILE} ${SOURCE_FILE})
