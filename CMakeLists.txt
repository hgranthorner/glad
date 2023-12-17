cmake_minimum_required(VERSION 3.27)
project(glad LANGUAGES C)

add_library(glad STATIC src/gl.c)
target_include_directories(glad PUBLIC include)
