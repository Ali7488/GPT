cmake_minimum_required(VERSION 3.16)

project(GPT LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)

add_executable(run src/main.cpp src/util.cpp)

target_include_directories(run PRIVATE Include)