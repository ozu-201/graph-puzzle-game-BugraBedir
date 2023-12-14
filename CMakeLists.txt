cmake_minimum_required(VERSION 3.23)
project(graph-puzzle-game-BugraBedir)

set(CMAKE_CXX_STANDARD 17)

add_executable(Edge.cpp Edge.h EdgeList.cpp EdgeList.h main.cpp src/List/Graph/Graph.cpp)
