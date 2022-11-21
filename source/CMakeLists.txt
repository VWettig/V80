cmake_minimum_required(VERSION 3.6)
project(V80 VERSION 0.1 LANGUAGES CXX)
set(CMAKE_CXX_STANDARD 17)


add_executable(v80
    "${CMAKE_SOURCE_DIR}/src/Main.cc"
)
target_include_directories(v80 PRIVATE "${CMAKE_SOURCE_DIR}/include")