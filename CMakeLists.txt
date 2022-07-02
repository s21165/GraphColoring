cmake_minimum_required(VERSION 3.20)
project(AI_C__)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)
include_directories(.idea)

add_executable(AI_C__
        .idea/.gitignore
        ".idea/AI C++.iml"
        .idea/modules.xml
        .idea/workspace.xml
        main.cpp)
