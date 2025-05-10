cmake_minimum_required(VERSION 3.21)
project(advanced_label)

set(CMAKE_CXX_STANDARD 20)

add_library(${PROJECT_NAME} INTERFACE src/AdvancedLabel.cpp)
target_include_directories(${PROJECT_NAME} INTERFACE include)