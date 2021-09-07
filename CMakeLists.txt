cmake_minimum_required(VERSION 3.0.0)
project(CMake Tools VERSION 0.1.0)

include(CTest)
enable_testing()

add_executable(CMake Tools main.cpp)

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)
