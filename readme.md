## Purpose And Functions
- This Library is built for the learning the directories structure and library building.
- This library has simple function printHello():-> prints hello world
### How to include
- Clone this repo
```
git clone https://github.com/suryanshvermaa/Hello-World-library-cpp.git
```
#### Add to your project
```
cd Hello-world-library-cpp
mkdir build
cd build
cmake ..
make
```
#### Add to your CMakeLists.txt file

target_link_libraries(main
    PRIVATE
    hello-world
) \n
add_subdirectory(Hello-world-library-cpp)
