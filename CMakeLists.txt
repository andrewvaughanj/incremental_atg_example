cmake_minimum_required(VERSION 3.11.4)

project (incremental_atg)

add_library(incremental_atg src/function_change.c src/global_change.c src/header_change.c src/no_change.c)

target_include_directories(incremental_atg PRIVATE "${CMAKE_SOURCE_DIR}/inc")

# EOF
