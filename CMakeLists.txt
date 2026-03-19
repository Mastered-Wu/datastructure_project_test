cmake_minimum_required(VERSION 3.10)

project(CPPProject)

set(CMAKE_CXX_STANDARD 17)

# 头文件目录
include_directories(include)

# 可执行程序
add_executable(main
    src/main.cpp
)