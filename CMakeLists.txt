cmake_minimum_required(VERSION 3.16)
project(L1a)

set(CMAKE_CXX_STANDARD 14)

add_executable(L1a main.cpp GraphUsingAdjacencyMatrix.cpp
        GraphUsingAdjacencyMatrix.h BFS.h CC.h DFS.h)