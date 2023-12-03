cmake_minimum_required(VERSION 3.26)
project(opencv_learning)

set(CMAKE_CXX_STANDARD 17)
set(OPENCV_DIR "D:/opencv/build")
set(OPENCV_INCLUDE_DIR "${OPENCV_DIR}/include")
set(OPENCV_LINK_DIR "${OPENCV_DIR}/x64/vc16/lib")
set(OPENCV_STATIC_LIB "opencv_world480d.lib")

add_subdirectory(lesson01)
