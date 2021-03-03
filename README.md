### Ofast

[List of packages that break with Ofast](https://github.com/N-R-K/Ofast/blob/master/package.env)

[How to setup per-package enviornment variable in gentoo](https://wiki.gentoo.org/wiki/Handbook:AMD64/Portage/Advanced#Per-package_environment_variables)

Keep in mind that just because you have Ofast set globally doesn't mean all packages will use it. Certain packages can silently override your cflags due to [flag filtering](https://wiki.gentoo.org/wiki/GCC_optimization#What_about_redundant_flags.3F)

Feel free to contribute to the list.
