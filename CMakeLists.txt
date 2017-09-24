cmake_minimum_required(VERSION 3.5)

# SET(CMAKE_BUILD_TYPE Debug CACHE STRING "Build setting")
set(CMAKE_CXX_STANDARD 11)
project(NTRIPSERVER)

add_executable(ntripserver
    ntripserver.c
)

target_link_libraries(
    ntripserver
)

install(TARGETS ntripserver DESTINATION bin)
