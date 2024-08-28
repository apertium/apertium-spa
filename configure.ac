AC_PREREQ(2.52)

AC_INIT([Apertium Spanish], [1.3.0], [apertium-stuff@lists.sourceforge.net], [apertium-spa], [https://wiki.apertium.org/wiki/Apertium-spa])
AM_INIT_AUTOMAKE
AC_PROG_AWK

PKG_CHECK_MODULES(APERTIUM, apertium >= 3.8.3)
PKG_CHECK_MODULES(APERTIUM_LEX_TOOLS, apertium-lex-tools >= 0.4.2)
PKG_CHECK_MODULES(LTTOOLBOX, lttoolbox >= 3.7.1)
PKG_CHECK_MODULES(CG3, cg3 >= 1.3.9)

PKG_CHECK_MODULES(REGTEST, apertium-regtest >= 0.9.1, [],
                  [AC_MSG_WARN([Running tests requires apertium-regtest])])

AP_MKINCLUDE

AC_OUTPUT([Makefile apertium-spa.pc])
