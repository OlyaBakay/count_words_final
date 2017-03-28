cmake_minimum_required(VERSION 3.6)
project(count_words_final)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp)
add_executable(count_words_final ${SOURCE_FILES})

TARGET_LINK_LIBRARIES( count_words_final pthread)