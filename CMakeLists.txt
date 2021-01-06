cmake_minimum_required(VERSION 3.0)

project(testgithublocal)

add_executable(testgithublocal main.cpp)

install(TARGETS testgithublocal RUNTIME DESTINATION bin)
