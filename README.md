# PPORTS - Package Ports

Package Ports, or pkgports (pports), is a package management system based on a collection of Makefiles.
Inspired by the classic BSD ports collection, it is designed to be simple, efficient, extensible, and highly configurable, offering users flexibility in managing software installations and configurations.

Basic usage:

```sh
pports <command> <path-to-package.mk>
```

Basic usage without shell helper:

```sh
make -f src/apps/pports/pports.mk <command> <path-to-package.mk>
```
