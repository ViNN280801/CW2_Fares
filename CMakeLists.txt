cmake_minimum_required(VERSION 3.22 FATAL_ERROR)

project(cw2_fares
    VERSION 1.0
    DESCRIPTION "Control work 2. X (unknown) variant. For Fares Nat."
    LANGUAGES C
)

set(CMAKE_C_STANDARD 17)
set(CMAKE_C_FLAGS "-lm -std=c17 -Wall -Wpedantic -Wextra")

add_executable(task1 task1.c)
add_executable(task2 task2.c)
add_executable(task3 task3.c)
