cmake_minimum_required(VERSION 2.8)

project (RNSD_GITLAB_FAQ
  LANGUAGES
    CXX
    C
    Fortran
)

set(CMAKE_DISABLE_SOURCE_CHANGES ON)

enable_testing()

add_subdirectory( src )
