cmake_minimum_required(VERSION 3.16)
project(entt)

add_library(entt SHARED src/entt.cpp)
target_include_directories(entt PUBLIC include)
