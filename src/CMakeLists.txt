project(HelloWorld)

add_library(hello-world printHello.cpp)

target_include_directories(
    hello-world
    PUBLIC
    ${CMAKE_CURRENT_SOURCE_DIR}/../include
)