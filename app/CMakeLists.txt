include_directories(include)

set(cptr_SOURCES src/cptr.c)

add_executable(cptr ${cptr_SOURCES})

install(TARGETS cptr DESTINATION bin)

message(STATUS "Will install cptr in ${CMAKE_INSTALL_PREFIX}/bin")