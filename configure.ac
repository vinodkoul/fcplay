#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.63])
AC_INIT([fcplay], [0.0.1])
AC_CONFIG_HEADERS([config.h])
AC_CONFIG_MACRO_DIR([m4])

AM_INIT_AUTOMAKE(1.10)
LT_INIT(disable-static)

# Checks for programs.
AC_PROG_CXX
AC_PROG_CC
AC_PROG_CPP
AC_PROG_INSTALL
AC_PROG_MAKE_SET
AM_PROG_CC_C_O

# Checks for libraries.
PKG_CHECK_MODULES([AVCODEC], [libavcodec >= 3.0.7])
PKG_CHECK_MODULES([AVFORMAT], [libavformat >= 3.0.7])
PKG_CHECK_MODULES([AVUTIL], [libavutil >= 3.0.7])
PKG_CHECK_MODULES([TINYCOMPRESS], [tinycompress >= 0.1.7])

# Checks for typedefs, structures, and compiler characteristics.

# Checks for library functions.

AC_CONFIG_FILES([
Makefile
include/Makefile
src/Makefile])
AC_OUTPUT
