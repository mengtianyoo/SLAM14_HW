# least veesion
cmake_minimum_required(VERSION 2.8)

# name
project(HelloSLAM)

# exe
add_executable( helloSLAM helloSLAM.cpp )
add_executable( useHello useHello.cpp )
target_link_libraries( useHello hello)

#lib
add_library( hello libHelloSLAM.cpp )