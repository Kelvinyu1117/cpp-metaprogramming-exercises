cmake_minimum_required(VERSION 3.14.0)

project(CppMetaExercises LANGUAGES CXX C)

set(EXECUTABLE_OUTPUT_PATH ${CMAKE_BINARY_DIR}/bin)
set(CMAKE_C_STANDARD 99)
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_FLAGS "-Wall")
subdirs(src)
