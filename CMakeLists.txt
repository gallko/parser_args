cmake_minimum_required(VERSION 3.10)
project(parser_args)

set(CMAKE_CXX_STANDARD 11)

add_library(parser_args STATIC ParserArgs.cpp)