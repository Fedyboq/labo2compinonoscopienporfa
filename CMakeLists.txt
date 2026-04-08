cmake_minimum_required(VERSION 3.31)
project(Prueba2)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Prueba2
        ast.cpp
        ast.h
        main.cpp
        parser.cpp
        parser.h
        scanner.cpp
        scanner.h
        token.cpp
        token.h)
