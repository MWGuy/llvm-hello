cmake_minimum_required(VERSION 3.14)
project(llvm_hello)

set(CMAKE_CXX_FLAGS -lLLVM) # link LLVM libs
add_executable(llvm_hello main.cpp)