project(HelloWorld)

add_executable(hello_world_example hello_world_example.cpp)

target_link_libraries(hello_world_example
    PRIVATE
    hello-world
)