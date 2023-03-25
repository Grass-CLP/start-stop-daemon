cmake_minimum_required(VERSION 3.16)
project(start_stop_daemon C)

set(CMAKE_C_STANDARD 11)

add_executable(start_stop_daemon
        start-stop-daemon.c
        start-stop-daemon.dpkg.c)
