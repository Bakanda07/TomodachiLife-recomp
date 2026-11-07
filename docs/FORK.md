# About this fork

This is a fork of [josiahg2502-glitch/TomodachiLife-recomp](https://github.com/josiahg2502-glitch/TomodachiLife-recomp), maintained by Bakanda07 as a continuation of the open-source project. It carries the upstream work as it stood on the date below.

- Game / target: Tomodachi Life: Living the Dream (Switch, AArch64)
- Licence: GPL-3.0. The licence file and the author notices of the upstream repository are kept as they are.
- Base commit: `b7ba15075e7303f79b2f941f09d30003f49aa80c` (b7ba150, 2026-11-06: "Pin the runtime package of this version")
- Base tag: `upstream-base-2026-11-07` marks that commit in this repository.
- Default branch: `main`

## What differs from upstream

None. `main` is identical to upstream at the base commit.

## Releases and mirrors

Releases v0.1.1-beta to v1.0.3 are mirrored on this account (assets copied unchanged from the author). Branch `mirror-bakanda07` (1 commit) repoints the installer, updater and download scripts to this account; it is not merged into `main` yet.

Releases published here before any change of ours are copies of the upstream builds. They are not built from this repository.

## Following upstream

```sh
git fetch upstream
git log --oneline main..upstream/main
git merge --ff-only upstream/main
```

## Rules for this fork

- No game data, keys, extracted files or code generated from a game goes into this repository.
- A release built from this fork must say so in its name or notes and give the base tag it started from.
- Changes of ours are listed in the section above when they are merged.
