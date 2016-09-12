cmake_minimum_required(VERSION 2.6)
project(rob_live_chat)

add_executable(rob_live_chat main.cpp)

install(TARGETS rob_live_chat RUNTIME DESTINATION bin)
