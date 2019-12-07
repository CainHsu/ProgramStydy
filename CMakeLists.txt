# cmake_minimum_required(VERSION <specify CMake version here>)
project(Test)

set(CMAKE_CXX_STANDARD 11)

add_executable(Test main.cpp ListNode.hpp matrix.hpp "leetCode/75.Sort Colors.hpp"
        hash.hpp stack.hpp "leetCode/739.Daily Temperatures.hpp" "leetCode/20.Valid Parentheses.hpp")