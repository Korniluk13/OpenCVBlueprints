cmake_minimum_required(VERSION 2.8)
project( iris_recognition )
find_package( OpenCV REQUIRED )
add_executable( iris_recognition iris_recognition.cpp )
target_link_libraries( iris_recognition ${OpenCV_LIBS} )
