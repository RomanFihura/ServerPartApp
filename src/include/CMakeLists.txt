cmake_minimum_required(VERSION 3.10)
project(ServerClientApp)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

add_subdirectory(src/common)
add_subdirectory(src/server)
add_subdirectory(src/client)
