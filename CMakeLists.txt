set_property(GLOBAL PROPERTY USE_FOLDERS ON)
set_property(GLOBAL PROPERTY PREFIX_FOLDERS ON)

cmake_minimum_required(VERSION 3.5 FATAL_ERROR)

project(Foo CXX)

add_subdirectory(subdir)

add_library(foo foo.cpp)
