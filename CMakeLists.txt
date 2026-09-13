cmake_minimum_required(VERSION 3.10)

project(sdl3-3d)

find_package(SDL3 CONFIG REQUIRED)

add_executable(3d main.c)

target_link_libraries(3d PRIVATE SDL3::SDL3)
