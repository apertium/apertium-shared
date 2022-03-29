AC_PREREQ(2.52)

AC_INIT([Apertium Shared], [0.1.0], [apertium-stuff@lists.sourceforge.net], [apertium-shared], [https://wiki.apertium.org/])
AM_INIT_AUTOMAKE

PKG_CHECK_MODULES(APERTIUM, apertium >= 3.8.1)
PKG_CHECK_MODULES(LTTOOLBOX, lttoolbox >= 3.6.3)

AC_OUTPUT([Makefile src/Makefile apertium-shared.pc])
