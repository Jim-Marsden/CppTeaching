cmake_minimum_required(VERSION 3.20)
project(CppTeaching)

set(CMAKE_CXX_STANDARD 17)
add_subdirectory(lesson_1)
add_subdirectory(lesson_2_types)
add_subdirectory(lesson_3_input_output)
add_subdirectory(lesson_4_functions)
add_subdirectory(lesson_5_strings)
add_subdirectory(lesson_6_vectors)
add_subdirectory(lesson_7_ref)

add_executable(CppTeaching main.cpp)
