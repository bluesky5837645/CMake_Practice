project(hello)
set(SRC_LIST main.c)
message(STATUS "The binary dir is: " ${HELLO_BIINARY_DIR})
message(STATUS "The SOURCE dir is: " ${HELLO_SOURCE_DIR})
add_executable(hello ${SRC_LIST})