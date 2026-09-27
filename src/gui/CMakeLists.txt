cmake_minimum_required(VERSION 3.20)
project(gui)

add_library(${PROJECT_NAME}
    gui.cpp
)

target_include_directories(${PROJECT_NAME} PUBLIC
    ${CMAKE_CURRENT_SOURCE_DIR}
)