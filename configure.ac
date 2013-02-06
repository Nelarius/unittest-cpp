#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT([UnitTest++], [1.4], [victor.lavaud@gmail.com])
AC_CONFIG_SRCDIR([src/TestDetails.cpp])
AC_CONFIG_HEADERS([config.h])

AM_INIT_AUTOMAKE()
LT_INIT()

AC_SUBST([LIBUNITTEST_SO_VERSION], [1:4:0])

# Checks for programs.
AC_PROG_CXX
AC_PROG_CC

# Checks for libraries.

# Checks for header files.
AC_CHECK_HEADERS([sys/time.h unistd.h setjmp.h signal.h cassert cstddef cstdio cstring exception iosfwd iostream sstream string vector])

# Checks for typedefs, structures, and compiler characteristics.
AC_CHECK_HEADER_STDBOOL
AC_C_INLINE
AC_TYPE_SIZE_T

# Checks for library functions.
AC_CHECK_FUNCS([gettimeofday strstr])

AC_CONFIG_FILES([Makefile
		 src/Makefile])
AC_OUTPUT