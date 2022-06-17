add_library(libexplode STATIC explode.c)
target_link_libraries(libexplode
    PRIVATE include)
