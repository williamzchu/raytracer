cmake_minimum_required(VERSION 3.10)

project("Raytracer")

# Set the C++ standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

set(SOURCE_FILES main.cpp)
# Add the executable
add_executable(Raytracer main.cpp)

