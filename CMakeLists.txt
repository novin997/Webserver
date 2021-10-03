cmake_minimum_required (VERSION 2.8.11)
project (Webserver)

include_directories(include)

# set(SOURCES src/main.cpp)

file(GLOB SOURCES "src/*.cpp")

add_executable(webserver ${SOURCES})