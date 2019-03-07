# you should ALWAYS declare the minimum required cmake version
# as the first thing you do in a project
cmake_minimum_required(VERSION 3.5)

# project statement sets up some variables
# you can set some variables here, but you'll rarely need to touch this
project(hello-world)

# create a new executable target
# the resultant binary might have a slightly different
# name depending on the platform, for example on windows
# this will produce a file hello-world-exe.exe
add_executable(hello-world-exe # with this name
  # and this list of sources
  src/main.cpp)
