project(blah)

add_library(${PROJECT_NAME} SHARED
    blah.h blah.cpp)

target_include_directories(${PROJECT_NAME} PRIVATE .)

target_include_directories(${PROJECT_NAME} PUBLIC ../)
