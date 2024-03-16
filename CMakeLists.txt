cmake_minimum_required(VERSION 3.26)
project(OpenGL-Test)

set(CMAKE_CXX_STANDARD 23)

add_subdirectory(libs)
add_executable(OpenGL-Test main.cpp)

target_link_libraries(OpenGL-Test PRIVATE glm glfw glad)
