cmake_minimum_required(VERSION 3.10)  # Specify the minimum version of CMake required
project(ImplementWebRequestInC-Curl)  # Define your project name

set(SRC_DIR ${CMAKE_CURRENT_SOURCE_DIR}/src)

set(SRC_FILES ${SRC_DIR}/main.c)

# Add your source files here (e.g., main.cpp, other sources)
add_executable(${PROJECT_NAME} ${SRC_FILES})
