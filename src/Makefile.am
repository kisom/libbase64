ACLOCAL_AMFLAGS = -Im4
AM_CFLAGS = -Werror -Wall -std=c99 -D_XOPEN_SOURCE=700 -D_BSD_SOURCE -D_DEFAULT_SOURCE

lib_LTLIBRARIES = libbase64.la
libbase64_la_SOURCES = base64.c
libbase64_la_LDFLAGS = -version-info 0:0:0
include_HEADERS = base64.h

pkgconfig_DATA = libbase64-1.pc
