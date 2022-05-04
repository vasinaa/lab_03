cmake_minimum_required(VERSION 3.10)

project(hello_world)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

include_directories("../formatter_ex_lib")
include_directories("../formatter_lib")

add_library(formatter STATIC "../formatter_lib/formatter.cpp" "../formatter_lib/formatter.h")
