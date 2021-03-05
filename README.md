### Ofast

[List of packages that break with Ofast](https://github.com/N-R-K/Ofast/blob/master/package.env)

[How to setup per-package environment variable in gentoo](https://wiki.gentoo.org/wiki/Handbook:AMD64/Portage/Advanced#Per-package_environment_variables)

Keep in mind that just because you have Ofast set globally doesn't mean all packages will compile with it. Certain packages can silently override your CFLAGS due to [flag filtering.](https://wiki.gentoo.org/wiki/GCC_optimization#What_about_redundant_flags.3F)

Also keep in mind that higher O levels apply *more* optimizations, not necessarily *better* optimizations. Ofast (or even O3) can sometimes worsen performance due to producing larger binary.

Feel free to contribute to the list.

### Misc resources:

- [GCC 11 Optimization Benchmarks](https://www.phoronix.com/scan.php?page=article&item=amd-5950x-gcc11&num=2)
- [Gentoo wiki: GCC optimization](https://wiki.gentoo.org/wiki/GCC_optimization)
- [GentooLTO](https://github.com/InBetweenNames/gentooLTO)
