cmake_minimum_required(VERSION 3.5 FATAL_ERROR)

project(Foo NONE)

add_subdirectory(subdir)

add_library(foo foo.cpp)
