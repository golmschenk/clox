cmake_minimum_required(VERSION 3.23)
project(clox C)

set(CMAKE_C_STANDARD 17)

add_executable(clox main.c chunk.h chunk.c memory.h
        memory.c
        debug.c
        debug.h
        value.c
        value.h)
