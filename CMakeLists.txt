cmake_minimum_required(VERSION 3.11 FATAL_ERROR)

project(cptr)

set (cptr_VERSION_MAJOR 0)
set (cptr_VERSION_MINOR 1)

include_directories(include)

set(cptr_SOURCES src/cptr.c)

add_executable(cptr ${cptr_SOURCES})

add_subdirectory(fastmath)

target_link_libraries(fastmath)
