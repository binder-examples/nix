# [Nixpkgs](https://github.com/nixos/nixpkgs) BinderHub example

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/binder-examples/nix/master)

# Why Nix?

[Nix](https://github.com/nixos/nixpkgs) would be a great addition to reproducible data science. It is a unique package manager. Some notable features:

 - 100% reproducible environments (pin to exact commit in repository)
 - both a source and binary package repository
 - allows customized compilation and version of every package
 - can run identical environment outside of docker (all linux distros + dawin)
 - as of now [45,000+ packages](https://repology.org/repositories/statistics/total)
 - fully declarative environments
 - packages: python, javascript, julia, R, haskell, perl, and many other languages (some better than others).

Assuming that you have [`nix`
installed](https://nixos.org/nix/download.html) (compatible with all
linux distributions and darwin (Mac OS)) you can run this repository
locally (no need for binderhub). It will be identical assuming you
have pinned repositories. Nix can coexist fine with other package
managers.

This derivation installs `python37`, `numpy`, and `scipy`.

For a more detailed example see the detailed [binderhub example costrouc/nix-binder-example](https://github.com/costrouc/nix-binder-example)
