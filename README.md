# oprt - tools to manage CRUX ports

Tool | Description
-|-
[oprt-cleanup(1)](src/oprt-cleanup.1.pod) | cleanup stuff
[oprt-collections(1)](src/oprt-collections.1.pod) | better alternative to `echo /usr/ports/*/port`
[oprt-depinst(8)](src/oprt-depinst.8.pod) | better alternative to `prt-get depinst`
[oprt-deporder(1)](src/oprt-deporder.1.pod) | post-processed deptree
[oprt-depsearch(1)](src/oprt-depsearch.1.pod) | better alternative to `grep '# Depends.*port' /usr/ports/*/Pkgfile`
[oprt-deptree(1)](src/oprt-deptree.1.pod) | show dependencies tree
[oprt-diff(1)](src/oprt-diff.1.pod) | show outdated ports
[oprt-dsearch(1)](src/oprt-dsearch.1.pod) | better alternative to `grep '^# Description.*expr' /usr/ports/*/Pkgfile`
[oprt-fsearch(1)](src/oprt-fsearch.1.pod) | better alternative to `grep expr /usr/ports/*/.footprint`
[oprt-info(1)](src/oprt-info.1.pod) | better alternative to `cat /usr/ports/*/port/Pkgfile`
[oprt-info-all(1)](src/oprt-info-all.1.pod) | better alternative to `cat /usr/ports/*/port/*`
[oprt-install(8)](src/oprt-install.8.pod) | better alternative to `pkgmk -d -i`
[oprt-pkgfile-deps(1)](src/oprt-pkgfile-deps.1.pod) | better alternative to `awk FS='Depends on:' '(1 < NF) {print $2}' Pkgfile`
[oprt-reinstall(8)](src/oprt-reinstall.8.pod) | better alternative to `pkgmk -d -f -u`
[oprt-remove(8)](src/oprt-remove.8.pod) | better alternative to `pkgrm port`
[oprt-search(1)](src/oprt-search.1.pod) | better alternative to `echo /usr/ports/*/*expr*`
[oprt-update(8)](src/oprt-update.8.pod) | better alternative to `prt-get sysup`
[oprt-watch(8)](src/oprt-watch.8.pod) | better alternative to `ck4up`
[pp(1)](src/pp.1.pod) | patch CRUX ports
[prtcheckedits(1)](src/prtcheckedits.1.pod) | print modified files (installed with pkgutils)
[prtchecknew(1)](src/prtchecknew.1.pod) | print local/new files (not installed with pkgutils)
[upkgmk(1)](src/upkgmk.1.pod) | micro pkgmk, the easiest way to build a port
