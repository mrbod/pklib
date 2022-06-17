add_library(libimplode STATIC implode.c)
target_link_libraries(libimplode
    PRIVATE include)
