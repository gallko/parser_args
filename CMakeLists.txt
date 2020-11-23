cmake_minimum_required(VERSION 3.10)
project(parser_args)

add_library(${PROJECT_NAME} STATIC ParserArgs.cpp)

target_link_libraries(${PROJECT_NAME} INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})
add_library(test::ParserArgs ALIAS ${PROJECT_NAME})