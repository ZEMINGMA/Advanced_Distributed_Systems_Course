# CMake minimum version
cmake_minimum_required(VERSION 3.10)

# Project name
project(PaxosProtocol)

# Set C++ standard
set(CMAKE_CXX_STANDARD 17)

# Include directories
include_directories(include lib src)

# Find all source files
file(GLOB_RECURSE LIB_SOURCES lib/*.cpp)
file(GLOB_RECURSE PAXOS_SOURCES src/Paxos/*.cpp)
set(SOURCES src/main.cpp ${LIB_SOURCES} ${PAXOS_SOURCES})

# Output executable
add_executable(paxos ${SOURCES})
