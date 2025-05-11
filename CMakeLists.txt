cmake_minimum_required(VERSION 3.31)
project(PortScanner C)

set(CMAKE_C_STANDARD 17)

include_directories(include)
add_executable(PortScanner src/main.c)
