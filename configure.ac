AC_INIT([lxc-userns-scripts], [0.1])
AM_INIT_AUTOMAKE([subdir-objects foreign -Wall -Werror])

AC_CONFIG_SRCDIR([src/lxc-create-container.in])

AC_PROG_CC

AC_CONFIG_FILES([
    Makefile
    src/Makefile
    src/lxc-create-container
    src/hooks/Makefile
    src/hooks/sysprep
    src/hooks/userns-convert
    src/lib/Makefile
    src/lib/cfg.bash
    src/lib/id_map.bash
    src/lib/misc.bash
    src/lib/userns.bash
])

AC_OUTPUT
