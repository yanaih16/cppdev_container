cmake_minimum_required(VERSION 3.8)
project(cpp CXX)


add_executable(main main.cpp)

target_compile_options(main PUBLIC -Wall -Wextra -O2)

target_compile_features(main PUBLIC cxx_std_17)