set(CMAKE_CXX_FLAGS "-Wall -std=c++11")
cmake_minimum_required(VERSION 3.5.1)
project (Minesweeper)

add_executable(Shell shell.cpp)
target_link_libraries(Shell gtest gtest_main)
