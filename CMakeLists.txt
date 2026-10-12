cmake_minimum_required(VERSION 4.3)
project(Logger CXX)

set(CMAKE_CXX_STANDARD 26)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

add_compile_options(-Wall -Wextra -Wpendant -Wconversion)

add_executable(Logger
        src/main.cpp
        src/logger.cpp)

enable_testing()