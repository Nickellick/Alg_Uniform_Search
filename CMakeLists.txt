cmake_minimum_required(VERSION 3.14)
project(Alg_Uniform_Search C)

set(CMAKE_C_STANDARD 11)

add_executable(Alg_Uniform_Search main.c)
target_link_libraries(Alg_Uniform_Search m quadmath)