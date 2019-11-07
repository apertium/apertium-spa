AC_PREREQ(2.52)

AC_INIT([Apertium Spanish], [1.2.0], [apertium-stuff@lists.sourceforge.net], [apertium-spa], [http://wiki.apertium.org/wiki/Apertium-spa])
AM_INIT_AUTOMAKE

AC_PROG_AWK

PKG_CHECK_MODULES(APERTIUM, apertium >= 3.6.0)
PKG_CHECK_MODULES(APERTIUM_LEX_TOOLS, apertium-lex-tools >= 0.2.2)
PKG_CHECK_MODULES(LTTOOLBOX, lttoolbox >= 3.5.0)
PKG_CHECK_MODULES(CG3, cg3 >= 1.3.0)

AP_MKINCLUDE

AC_OUTPUT([Makefile apertium-spa.pc])
