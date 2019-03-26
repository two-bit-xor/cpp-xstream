cmake_minimum_required(VERSION 3.13)
project(cpp_xstream)

set(CMAKE_CXX_STANDARD 17)

add_library(cpp_xstream hello-world.cpp hello-world.h src/binance/binance-websocket.cpp src/binance/binance-websocket.h)