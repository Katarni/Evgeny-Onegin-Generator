cmake_minimum_required(VERSION 3.26)
project(EvgenyOneginGenerator)

set(CMAKE_CXX_STANDARD 17)

add_executable(EvgenyOneginGenerator main.cpp
        Line.cpp
        Line.h
        Poem.cpp
        Poem.h)
