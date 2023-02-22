cmake_minimum_required(VERSION 3.22.0)

project(figures)

add_library(header 
classes/EquilateralTriangle.cpp 
classes/error_create_figure.cpp 
classes/Figure.cpp 
classes/IsoscelesTriangle.cpp 
classes/Parallelogram.cpp 
classes/Quadrilateral.cpp 
classes/Rectangle.cpp 
classes/Rhombus.cpp 
classes/RightTriangle.cpp 
classes/Square.cpp 
classes/Triangle.cpp)

add_executable(Figures main.cpp)

target_link_libraries(Figures header)