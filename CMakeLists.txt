cmake_minimum_required (VERSION 2.6)
project (AMSG)

set (Sources main.cpp)
#set (Headers)
include_directories("${PROJECT_SOURCE_DIR}/inc")
add_executable(amsg ${Sources})