set(TOOLS_SRC
    error.h
    timer.h
    benchmark.h
)

add_library(tools-obj OBJECT ${TOOLS_SRC})
