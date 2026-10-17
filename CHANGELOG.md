# Changelog

## [0.2.0](https://github.com/axelhamil/nixos-starter/compare/v0.1.0...v0.2.0) (2026-10-17)


### Features

* **desktop:** print to network printers without installing a driver ([27fb7a6](https://github.com/axelhamil/nixos-starter/commit/27fb7a6aeacaf4365ec6575676d963c2bb7ab9fc))
* **doctor:** check a machine and list what the next boot erases ([6cb9f91](https://github.com/axelhamil/nixos-starter/commit/6cb9f9130bb6fdef323bbba0eb4ab22251d4180c))
* **hibernate:** hibernate and suspend-then-hibernate to an encrypted swap ([bae35e2](https://github.com/axelhamil/nixos-starter/commit/bae35e2c664500e364b557f54ba213fb0ef9e150))
* **hosts:** read the installer's hardware report from a facter field ([259e744](https://github.com/axelhamil/nixos-starter/commit/259e744768d5404806ff9bce7f56ec51e71ed352))
* **init:** make a fresh fork yours with nix run .#init ([393eef3](https://github.com/axelhamil/nixos-starter/commit/393eef3d7edec7425a3277504c0b8052a1099699))
* **update:** keep forks and machines up to date every week ([#22](https://github.com/axelhamil/nixos-starter/issues/22)) ([2a1f389](https://github.com/axelhamil/nixos-starter/commit/2a1f38905251238d7180a3869ac7a2698fd1fdf2))


### Bug Fixes

* **doctor:** stop reporting links into /run as files lost at boot ([#25](https://github.com/axelhamil/nixos-starter/issues/25)) ([011ad7b](https://github.com/axelhamil/nixos-starter/commit/011ad7bf26ed6ea71358bc295f14bf85f2d6c871))
* **snapshots:** stop the hourly btrbk run from racing the snapshot test ([f20d37f](https://github.com/axelhamil/nixos-starter/commit/f20d37f8f559d122dbd17be834dcfb8be2e6a26f))

## 0.1.0 (2026-10-16)


### ⚠ BREAKING CHANGES

* declare hosts in a registry that generates their checks

### Features

* **boot:** enforce secure boot with lanzaboote and tpm unlock ([b363a62](https://github.com/axelhamil/nixos-starter/commit/b363a6277c56263ef4aa9350364a9d03b037da03))
* bootstrap a bootable nixos desktop flake ([9ac2350](https://github.com/axelhamil/nixos-starter/commit/9ac2350658250dfcf7360cd108ea9a65950367ee))
* **boot:** unlock the disk with the tpm2 without typing a command ([2bf1a34](https://github.com/axelhamil/nixos-starter/commit/2bf1a340f41bbbb13ba62c2a2ec1345fb6cc4286))
* declare hosts in a registry that generates their checks ([f0c956f](https://github.com/axelhamil/nixos-starter/commit/f0c956fb73088b893a08d144a3580a9d13e9d089))
* **desktop:** log in to a hyprland session from a text greeter ([b25f52a](https://github.com/axelhamil/nixos-starter/commit/b25f52a8a0ba0a3e27cdc89b21e4fda2abc9f399))
* **dev:** add nh, nix-index, rootless docker, libvirt, nix-ld and direnv ([51b7e65](https://github.com/axelhamil/nixos-starter/commit/51b7e65c5709c313b0788a844f2639d1ca3fc83c))
* **disk:** encrypt the disk and wipe / at every boot ([b6f6b5c](https://github.com/axelhamil/nixos-starter/commit/b6f6b5cc91e4f5432ef6a5f9703c3071d3f14a1e))
* **hardware:** add opt-in firmware, audio, bluetooth and gpu modules ([66e427b](https://github.com/axelhamil/nixos-starter/commit/66e427b5c19a3ce7ea94f71fe10677cadbb8308f))
* **home:** add a ready shell, XDG layout and dotfiles linking with stow ([ae38787](https://github.com/axelhamil/nixos-starter/commit/ae387871925860f5eb9e8f77c1f6ca63c8beb732))
* **home:** wipe /home at boot on opt-in, keeping only declared paths ([6116653](https://github.com/axelhamil/nixos-starter/commit/6116653174a290172ee40547e260dc05b61cfa46))
* **hosts:** describe a machine in one file of plain values ([a9c355a](https://github.com/axelhamil/nixos-starter/commit/a9c355a92da59f552ec7089252888349e1fb808d))
* **install:** install a host from a bootable iso that asks a few questions ([570448a](https://github.com/axelhamil/nixos-starter/commit/570448ad737e899740d9751b3e1c8c114c5babf9))
* lint, build and boot every host in CI ([#1](https://github.com/axelhamil/nixos-starter/issues/1)) ([e5c16f9](https://github.com/axelhamil/nixos-starter/commit/e5c16f948b8a271192b9f3ec5fec7bae249fe754))
* **perf:** add desktop, laptop and server profiles with a bench tool ([ad42996](https://github.com/axelhamil/nixos-starter/commit/ad429965ba444ca36108f7b363023f1d2bf7d6e8))
* **pi:** build a raspberry pi 4 or 5 sd card image from the starter ([f103c31](https://github.com/axelhamil/nixos-starter/commit/f103c31fbd53e9c0f4560a9db36f3ab7bf37877e))
* run each check on a runner matching its host system ([77a895c](https://github.com/axelhamil/nixos-starter/commit/77a895c2238b27df4226c3e77a523b02319121da))
* **services:** add resolved, btrbk snapshots, opt-in ssh and secrets ([f0b9721](https://github.com/axelhamil/nixos-starter/commit/f0b9721e2f064e3b2f2486746a1c4d9b3ddef395))


### Bug Fixes

* start the first release at 0.1.0 instead of 1.0.0 ([#2](https://github.com/axelhamil/nixos-starter/issues/2)) ([ed7683d](https://github.com/axelhamil/nixos-starter/commit/ed7683d247c86a57c8a52a000ebeb0b44ac7af46))
