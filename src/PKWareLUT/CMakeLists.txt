add_library(pkwareLUT STATIC PKWareLUTs.c)
target_link_libraries(pkwareLUT
    PRIVATE include)
