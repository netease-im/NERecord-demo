CMAKE_MINIMUM_REQUIRED(VERSION 3.0.0)

PROJECT(NERecord-demo VERSION 0.1.0)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED True)
set(CMAKE_VERBOSE_MAKEFILE ON)
INCLUDE_DIRECTORIES(${PROJECT_SOURCE_DIR}/NERecord-SDK/include)
LINK_DIRECTORIES(${PROJECT_SOURCE_DIR}/NERecord-SDK/lib64)

ADD_SUBDIRECTORY(src)

