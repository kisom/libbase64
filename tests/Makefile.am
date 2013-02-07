AM_CFLAGS = -I/usr/local/include -I../src
AM_CFLAGS += -D_XOPEN_SOURCE=700 -D_BSD_SOURCE -Werror -Wall
AM_LDFLAGS = -L/usr/local/lib

check_PROGRAMS = base64_test
base64_test_SOURCES = base64_test.c ../src/base64.c
base64_test_LDADD = -lcunit
