cmake_minimum_required(VERSION 3.15)

project(PKISystem C)

set(CMAKE_C_STANDARD 17)

include_directories(include)

add_executable(
    pki_system
    src/main.c
)