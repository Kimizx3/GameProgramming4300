cmake_minimum_required(VERSION 3.29)
project(Assign1)

set(CMAKE_CXX_STANDARD 20)

add_executable(Assign1 main.cpp)

find_package(SFML 2.6.1 COMPONENTS system window graphics network audio REQUIRED)

include_directories(/Users/ziyangk/Desktop/Code/SFML-2.6.1/imgui)
include_directories(/Users/ziyangk/Desktop/Code/SFML-2.6.1/imgui-sfml)
target_link_libraries(Assign1 sfml-system sfml-window sfml-graphics sfml-network sfml-audio ImGui-SFML ImGui)
