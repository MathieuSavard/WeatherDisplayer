cmake_minimum_required(VERSION 3.20)

project(RessourcesMonitor)

add_executable(${PROJECT_NAME} main.c binary_value.c)

target_include_directories(${PROJECT_NAME} PRIVATE ${CMAKE_SOURCE_DIR})