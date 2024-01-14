# CMakeLists.txt

cmake_minimum_required(VERSION 3.10)

project(HelloWorldProject)

# Set the source files
set(SOURCE_FILES
    src/main.c
    src/hello.c
)

# Set the include directories
include_directories(include)

# Create the executable
add_executable(hello_world ${SOURCE_FILES})
