cmake_minimum_required(VERSION 3.26)

project(lesson01)
set(CMAKE_CXX_STANDARD 17)
include_directories(${OPENCV_INCLUDE_DIR})
link_directories(${OPENCV_LINK_DIR})
link_libraries(${OPENCV_STATIC_LIB})
aux_source_directory(${CMAKE_CURRENT_SOURCE_DIR} SRC)
message(STATUS ${SRC})

add_executable(app ${SRC})
