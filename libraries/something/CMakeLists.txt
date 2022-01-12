project(something)

add_library(${PROJECT_NAME} SHARED
    something.h something.cpp)

target_include_directories(${PROJECT_NAME} PRIVATE .)

target_include_directories(${PROJECT_NAME} PUBLIC ../)
