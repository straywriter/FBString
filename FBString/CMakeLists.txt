cmake_minimum_required(VERSION 3.10)
project(FBString)

add_library(FBString INTERFACE)
target_include_directories(FBString INTERFACE ./)
target_link_libraries(FBString INTERFACE Boost::preprocessor)