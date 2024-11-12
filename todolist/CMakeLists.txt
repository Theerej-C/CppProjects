cmake_minimum_required(VERSION 3.10) 
project(todo)

set(SOURCE_DIR "src")
file(GLOB_RECURSE SOURCES "${SOURCE_DIR}/*.cpp")
add_executable(executable ${SOURCES})