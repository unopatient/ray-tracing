set (CMAKE_CXX_STANDARD 11)

cmake_minimum_required(VERSION 3.7...3.28)

if(${CMAKE_VERSION} VERSION_LESS 3.12)
    cmake_policy(VERSION ${CMAKE_MAJOR_VERSION}.${CMAKE_MINOR_VERSION})
endif()

project(weekend_raytracer)

add_executable(weekend_raytracer src/main.cpp)