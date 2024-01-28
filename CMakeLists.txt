cmake_minimum_required(VERSION 3.28.1)

project(Hello_world_program)

add_executable(hello-world main.c)

install(TARGETS hello-world DESTINATION bin)
