# $Id: configure.ac 21235 2007-02-06 13:51:02Z eriks $

m4_pattern_forbid([^META_])

AC_INIT
AC_CANONICAL_TARGET([])
META_SETUP
META_C_SETUP
AC_PROG_LIBTOOL

CURDATE=`date`
AC_SUBST([CURDATE])

AC_CHECK_FUNCS([strdup])
AC_CHECK_FUNCS([lrand48 srand48])

AC_CHECK_ALIGNOF([void *])
AC_CHECK_SIZEOF([void *])
AC_CHECK_SIZEOF([int])
AC_CHECK_SIZEOF([long])
AC_CHECK_SIZEOF([double])

AC_CONFIG_FILES([aterm.spec])

AC_OUTPUT
