cmake_minimum_required(VERSION 3.0)

project(OpenCV_test)  
find_package(OpenCV 3.2 REQUIRED)  
add_executable(main main.cpp)  
target_link_libraries(main ${OpenCV_LIBS})  