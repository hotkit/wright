cmake_minimum_required(VERSION 3.12)
project(wright)

# These contain targets and functions needed elsewhere
add_subdirectory(cord)
add_subdirectory(fost-base)

add_subdirectory(Boost)
add_subdirectory(crypto++)
add_subdirectory(fost-internet)
add_subdirectory(fost-wright)
add_subdirectory(threading)
