AC_PREREQ([2.69])

AC_INIT([demo-cpputest], [1.0], [])
AC_CONFIG_AUX_DIR([build-aux])

AM_INIT_AUTOMAKE([foreign dist-bzip2 subdir-objects 1.14])
AC_CONFIG_FILES([Makefile])
AM_SILENT_RULES([yes])

AC_PROG_CXX
AX_CXX_COMPILE_STDCXX_11([noext], [mandatory])
AX_CXX_HAVE_STL

PKG_CHECK_MODULES([CPPUTEST], [cpputest])

AC_OUTPUT
