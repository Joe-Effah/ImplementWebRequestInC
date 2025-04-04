cmake_minimum_required(VERSION 3.10)  
project(ImplementWebRequestInC-WinINet)  

set(SRC_DIR ${CMAKE_CURRENT_SOURCE_DIR}/src)
set(SRC_FILES ${SRC_DIR}/main.c)

add_executable(${PROJECT_NAME} ${SRC_FILES})
