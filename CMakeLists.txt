cmake_minimum_required(VERSION 3.18)

project(opengl-glad)

add_library(${PROJECT_NAME} STATIC src/gl.cpp)
target_include_directories(${PROJECT_NAME} PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/include)