cmake_minimum_required(VERSION 3.5)
project(Mango CXX)

set(CMAKE_CXX_STANDARD 23)

add_executable(Mango dire/main.cpp)

target_link_libraries(Mango PRIVATE ws2_32)