cmake_minimum_required(VERSION 3.6)
project(HelloWorld)

add_subdirectory(include)
add_subdirectory(src)

option(BUILD_EXAMPLES "Wheather or not to build examples" ON)

if(BUILD_EXAMPLES)
    message("Building examples...")
    add_subdirectory(examples)
endif()