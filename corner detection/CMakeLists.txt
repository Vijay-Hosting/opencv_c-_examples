cmake_minimum_required(VERSION 2.8)
project( fast )
find_package( OpenCV REQUIRED )
add_executable( fast fast_corners.cpp )
target_link_libraries( fast ${OpenCV_LIBS} )
