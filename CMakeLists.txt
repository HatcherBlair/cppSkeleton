cmake_minimum_required(VERSION 4.2.3)

project(pa1
    VERSION 0.0.1
    DESCRIPTION "Demo CPP App"
    LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED True)
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

add_executable(skeleton
	src/main.cpp
)

target_include_directories(skeleton PUBLIC include)
