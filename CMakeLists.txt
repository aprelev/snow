cmake_minimum_required(VERSION 3.2)

project(snow VERSION 2.3.0 LANGUAGES C)
add_library(snow INTERFACE)
target_include_directories(snow INTERFACE ${PROJECT_SOURCE_DIR}/include)
