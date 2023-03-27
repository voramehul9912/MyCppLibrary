cmake_minimum_required(VERSION 3.12)
project(MyCppLibrary)

add_library(MyCppLibrary SHARED
  hello.cpp
)

target_include_directories(MyCppLibrary PUBLIC include)
