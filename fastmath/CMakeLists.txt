
set(fastmath_HEADERS include/fastmath.h)
set(fastmath_SOURCES src/fastmath.c)

include_directories(include)

add_library(fastmath
	${fastmath_SOURCES}
	${fastmath_HEADERS})

target_include_directories(fastmath PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})