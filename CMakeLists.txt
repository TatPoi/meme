cmake_minimum_required(VERSION 3.4)
project(meme)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c99")

set(SOURCE_FILES main.c util.c)
add_executable(meme ${SOURCE_FILES})