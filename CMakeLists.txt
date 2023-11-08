cmake_minimum_required (VERSION 3.15)

project ("simpleConsoleToTestGHActions")

set(CMAKE_CXX_STANDARD 17)

set(Sources
    main.cpp)

add_executable (${PROJECT_NAME} ${Headers} ${Sources})