# cmake_minimum_required(VERSION <specify CMake version here>)
project(clox C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(clox
    chunk.c
    chunk.h
    common.h
    debug.c
    debug.h
    main.c
    memory.c
    memory.h
    value.c
    value.h
        vm.h
        vm.c
        compiler.h
        compiler.c
        scanner.h
        scanner.c
        object.h
        object.c
        table.h
        table.c)
