cmake_minimum_required(VERSION 3.21)
project(test)

set (VERSION "0.0.0.3")
file(WRITE version.txt ${VERSION})

add_executable (test-${VERSION} main.cpp)
