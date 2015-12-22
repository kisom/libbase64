AC_PREREQ([2.60])
AC_INIT([libbase64],
         [1.0.0],
         [kyle@tyrfingr.is],
         [],
         [https://github.com/kisom/libbase64])
AM_INIT_AUTOMAKE([1.11 foreign subdir-objects])

LT_INIT
AC_CONFIG_MACRO_DIRS([m4])

PKG_PROG_PKG_CONFIG
PKG_INSTALLDIR

AC_CONFIG_SRCDIR([src/base64.h])
AC_CONFIG_FILES([Makefile
                 src/Makefile
                 src/libbase64-1.pc
                 tests/Makefile
                 doc/Makefile])

AC_PROG_CC
AC_PROG_INSTALL

AC_OUTPUT
