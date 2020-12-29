cmake_minimum_required(VERSION 3.7)
project(untitled5 C)

set(CMAKE_C_STANDARD 99)

add_executable(untitled5 server/main.c trial/trialserver.c trial/trialclient.c trial/trialclient.h server/server.h server/server.c klient/client.c klient/client.h klient/main.c)
