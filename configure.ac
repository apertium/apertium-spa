AC_PREREQ(2.52)

AC_INIT([Apertium Spanish], [1.2.2], [apertium-stuff@lists.sourceforge.net], [apertium-spa], [https://wiki.apertium.org/wiki/Apertium-spa])
AM_INIT_AUTOMAKE
AC_PROG_AWK

PKG_CHECK_MODULES(APERTIUM, apertium >= 3.7.1)
PKG_CHECK_MODULES(APERTIUM_LEX_TOOLS, apertium-lex-tools >= 0.2.7)
PKG_CHECK_MODULES(LTTOOLBOX, lttoolbox >= 3.5.3)
PKG_CHECK_MODULES(CG3, cg3 >= 1.3.2)

AP_MKINCLUDE

AC_OUTPUT([Makefile apertium-spa.pc])
