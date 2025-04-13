cmake_minimum_required(VERSION 3.10)

project(CatanClone)

set(CMAKE_CXX_STANDARD 17)

find_package(SFML 2.5 COMPONENTS graphics window system REQUIRED)

add_executable(catan_clone
    src/main.cpp
)

target_link_libraries(catan_clone
    sfml-graphics
    sfml-window
    sfml-system
)
