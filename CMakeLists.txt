cmake_minimum_required(VERSION 3.21)
project(Tape)

set(CMAKE_CXX_STANDARD 20)

add_executable(Tape
        main.cpp
        TapeSorter.h
        TapeSorter.cpp
        TapeImpl.h
        TapeImpl.cpp
        TapeGenerator.h
        TapeGenerator.cpp
        TapeExceptions.h
        TapeExceptions.cpp
        Tape.h)
