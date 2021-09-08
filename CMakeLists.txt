cmake_minimum_required(VERSION 3.21)
project(test)

file (READ version.txt VERSION)
message ("Read version ${VERSION}")

add_executable (test-${VERSION} main.cpp)
