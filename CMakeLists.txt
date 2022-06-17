cmake_minimum_required(VERSION 3.13)

project("pklib")
set("PROJECT_DESCRIPTION" "Free open source PKWare Data Compression Library (DCL) compressor implementation")
set("PROJECT_HOMEPAGE_URL" "https://github.com/ladislav-zezula/StormLib/tree/master/src/pklib")

add_subdirectory(include)
add_subdirectory(src)

