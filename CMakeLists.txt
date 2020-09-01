cmake_minimum_required(VERSION 3.9) # CMP0069 NEW

project(croaring
  DESCRIPTION "croaring demo"
  LANGUAGES C CXX
)

set(CMAKE_C_STANDARD 11)
set(CMAKE_C_STANDARD_REQUIRED ON)
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_MACOSX_RPATH OFF)

set(PROJECT_VERSION_MAJOR 0)
set(PROJECT_VERSION_MINOR 0)
set(PROJECT_VERSION_PATCH 1)


add_library(croaring STATIC ${PROJECT_SOURCE_DIR}/dependencies/croaring/roaring.c)
target_include_directories(croaring PUBLIC ${PROJECT_SOURCE_DIR}/dependencies/croaring/)

add_subdirectory(src)