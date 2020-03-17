cmake_minimum_required(VERSION 3.10)

# set the project name and version
project(helloworld VERSION 1.0)

# add the executable
add_executable(HelloWorld helloworld.cpp)

#install config
install(TARGETS HelloWorld DESTINATION bin)