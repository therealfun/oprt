# oprt

oprt-cleanup (1)      - cleanup stuff
oprt-collections (1)  - better alternative to "echo /usr/ports/*/port"
oprt-depinst (8)      - better alternative to "prt-get depinst"
oprt-deporder (1)     - post-processed deptree
oprt-depsearch (1)    - better alternative to "grep '# Depends.*port' /usr/ports/*/Pkgfile"
oprt-deptree (1)      - show dependencies tree
oprt-diff (1)         - show outdated ports
oprt-dsearch (1)      - better alternative to "grep '^# Description.*expr' /usr/ports/*/Pkgfile"
oprt-fsearch (1)      - better alternative to "grep expr /usr/ports/*/.footprint"
oprt-info (1)         - better alternative to "cat /usr/ports/*/port/Pkgfile"
oprt-info-all (1)     - better alternative to "cat /usr/ports/*/port/*"
oprt-install (8)      - better alternative to "pkgmk -d -i"
oprt-pkgfile-deps (1) - better alternative to "awk FS='Depends on:' '(1 < NF) {print $2}' Pkgfile"
oprt-reinstall (8)    - better alternative to "pkgmk -d -f -u"
oprt-remove (8)       - better alternative to "pkgrm port"
oprt-search (1)       - better alternative to "echo /usr/ports/*/*expr*"
oprt-update (8)       - better alternative to "prt-get sysup"
oprt-watch (8)        - better alternative to "ck4up"
pp (1)                - patch CRUX ports
prtcheckedits (1)     - print modified files
prtchecknew (1)       - print local/new files (not installed)
upkgmk (1)            - micro pkgmk, the easiest way to build a port
