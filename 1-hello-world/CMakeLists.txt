# CMakeLists.txt
cmake_minimum_required(VERSION 3.10)  # Specifies the minimum version of CMake required

# Set the project name and version
project(HelloWorld VERSION 1.0)

# Specify the C standard
set(CMAKE_C_STANDARD 11)
set(CMAKE_C_STANDARD_REQUIRED True)

# Add an executable with the above sources
add_executable(hello_world main.c)
