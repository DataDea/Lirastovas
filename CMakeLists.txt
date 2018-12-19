cmake_minimum_required(VERSION 3.12)
project(io_model)

set(CMAKE_CXX_STANDARD 11)

add_executable(io_model main.cpp epoll/epoll-server.h epoll/epoll-client.h poll/poll-server.h poll/poll-client.h select/select-server.h select/select-client.h)