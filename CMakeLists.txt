cmake_minimum_required(VERSION 3.8)
project(lab4AllFiles)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        ArrayLib.h
        Lab4Tester.cpp
        TestLib.cpp
        TestLib.h ArrayLib.cpp)

add_executable(lab4AllFiles ${SOURCE_FILES})