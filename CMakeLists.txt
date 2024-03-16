cmake_minimum_required(VERSION 3.26)
project(untitled2)

set(CMAKE_CXX_STANDARD 23)

add_subdirectory(libs)
add_executable(untitled2 main.cpp)

target_link_libraries(untitled2 PRIVATE glm glfw glad)
