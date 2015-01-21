AC_INIT([lxc-userns-scripts], [0.4], [lxc-userns-scripts])
AM_INIT_AUTOMAKE([subdir-objects foreign -Wall -Werror])

AC_CONFIG_SRCDIR([src/lxc-create-with-userns.in])

AC_PROG_CC

AC_SUBST(pkgdatadir, $datadir/[AC_PACKAGE_NAME])

AC_CONFIG_FILES([
	Makefile
	src/Makefile
	src/lxc-create-with-userns
	src/hooks/Makefile
	src/hooks/sysprep
	src/hooks/userns-convert
	src/hooks/userns-allow
	src/lib/Makefile
	src/lib/cfg.sh
	src/lib/id_map.sh
	src/lib/misc.sh
	src/lib/userns.sh
])

AC_OUTPUT
