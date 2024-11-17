# Lime3DS Package

The [Lime3DS](https://github.com/Lime3DS/lime3ds-archive) emulator for the [Nintendo 3DS](https://wikipedia.org/wiki/Nintendo_3DS) console got discontinued in favor of the [Azahar](https://github.com/azahar-emu/azahar) emulator.

This package provides an updated [PKGBUILD](https://wiki.archlinux.org/title/PKGBUILD) for the `lime3ds` package (primary for [Arch Linux](https://archlinux.org/); this will maybe work on your Linux distribution too).

I made this package because I am not sure when (or even if) the [`lime3ds`](https://aur.archlinux.org/packages/lime3ds) package from the AUR will be updated, and I wanted to use the latest Lime3DS version.

## Changes

I made the following changes to the PKGBUILD file:

- update maintainer and fork-notice
- change "experimental" to "discontinued" in `pkgdesc`
- change the `url` to the new [GitHub-repository](https://github.com/Lime3DS/lime3ds-archive)
- break down the the `depends` array to one line
- update the repository name in the `source` array
- change the checksum from MD5 to SHA256

## Legal Notice

I am not affiliated with

- the lime3ds AUR package,
- the Lime3DS project,
- the Azahar project nor
- Nintendo.

For more information on the PKGBUILD's license see [LICENSE.md](./LICENSE.md)