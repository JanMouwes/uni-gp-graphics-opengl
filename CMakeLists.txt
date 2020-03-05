cmake_minimum_required(VERSION 3.15)
project(OpenGL)

set(CMAKE_CXX_STANDARD 14)

include_directories(libraries/glew-2.0.0-win32/glew-2.0.0/include)
include_directories(libraries/freeglut-MSVC-3.0.0-2.mp/freeglut/include)


add_executable(OpenGL Program1/main.cpp)