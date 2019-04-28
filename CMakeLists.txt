cmake_minimum_required(VERSION 3.0)
project(valve-bsp-parser VERSION 0.0.1)
add_library(valve-bsp-parser STATIC "${PROJECT_SOURCE_DIR}/ValveBSP/TraceRay.cpp" "${PROJECT_SOURCE_DIR}/ValveBSP/BSPFile.cpp")
target_include_directories(valve-bsp-parser PRIVATE "${PROJECT_SOURCE_DIR}/ValveBSP")
