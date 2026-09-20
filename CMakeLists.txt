cmake_minimum_required(VERSION 4.3)
project(encounter_analyzer)

set(CMAKE_CXX_STANDARD 20)

add_executable(encounter_analyzer main.cpp)

target_link_options(encounter_analyzer PRIVATE -static-libgcc -static-libstdc++)