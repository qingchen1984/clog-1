AC_INIT([clog], [0.0.0])
AM_INIT_AUTOMAKE

AC_SUBST([pkgconfigdir], ['${libdir}/pkgconfig'])

: ${CFLAGS:=-g -Wall}

AC_PROG_CC
AM_PROG_CC_C_O
LT_INIT

PKG_CHECK_MODULES([GLIB], [glib-2.0])

AC_CONFIG_FILES([ \
  Makefile \
  clog/Makefile \
])
AC_CONFIG_FILES([clog.pc])
AC_OUTPUT
