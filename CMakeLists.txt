cmake_minimum_required(VERSION 3.23)

project(raytracing)
add_executable(raytracing)
target_sources(raytracing
    PRIVATE
        raytracing.cpp
)