cmake_minimum_required(VERSION 3.19)
project(crafting_interpreters_clox C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(crafting_interpreters_clox
        chunk.c
        chunk.h
        memory.c
        memory.h
        common.h
        debug.c
        debug.h
        value.c
        value.h
        main.c)
