cmake_minimum_required(VERSION 2.8)
project(picosha2-test)

set(CMAKE_CXX_STANDARD 11)

set(CMAKE_CXX_FLAGS "-Wall -Wextra")

add_executable(${PROJECT_NAME} test.cpp)
