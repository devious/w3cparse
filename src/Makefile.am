AM_CFLAGS = -Wall -Wextra -pedantic -Wshadow -Wpointer-arith -Wcast-align \
            -Wwrite-strings -Wmissing-prototypes -Wmissing-declarations   \
            -Wredundant-decls -Wnested-externs -Winline -Wno-long-long    \
            -Wconversion -Wstrict-prototypes -g -O0
lib_LIBRARIES = libw3cparse.a
include_HEADERS = w3cparse.h
check_PROGRAMS = test_parse
libw3cparse_a_SOURCES = core.cc
test_parse_SOURCES = test_parse.cc
test_parse_LDADD = libw3cparse.a
test_parse_CFLAGS = -O0


