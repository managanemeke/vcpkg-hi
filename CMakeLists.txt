cmake_minimum_required(VERSION 3.10)

project(hi)

find_package(fmt CONFIG REQUIRED)

add_executable(hi hi.cpp)

target_link_libraries(hi PRIVATE fmt::fmt)
