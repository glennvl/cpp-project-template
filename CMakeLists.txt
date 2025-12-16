cmake_minimum_required(VERSION 4.2 FATAL_ERROR)

include("${CMAKE_CURRENT_LIST_DIR}/cmake/cpprog.cmake")

cpprog_init()

project(CppProjectTemplate VERSION 0.0.1 LANGUAGES C CXX)

cpprog_configure_project()

add_subdirectory(src)
add_subdirectory(tests)
