cmake_minimum_required(VERSION 2.8)

project(test_app_2)

add_executable(testapp2 main.cpp)

install(TARGETS testapp2 DESTINATION bin)

