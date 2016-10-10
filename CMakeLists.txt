cmake_minimum_required(VERSION 2.8)

project(TestTravis)

enable_testing()

add_executable(TestTravis TestTravis.cpp)
add_test(TestTravis TestTravis)
