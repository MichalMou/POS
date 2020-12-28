cmake_minimum_required(VERSION 3.7)
project(untitled5 C)

set(CMAKE_C_STANDARD 99)

add_executable(untitled5 server/main.c server/server.c klient/client.c klient/client.h)
