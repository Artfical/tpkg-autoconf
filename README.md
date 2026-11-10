# autoconf

GNU Autoconf 2.72

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install autoconf
```

| | |
|---|---|
| Version | 2.72 |
| Licence | GPL-3.0-or-later |
| Upstream | - |
| Needs | [`perl`](https://github.com/Artfical/tpkg-perl), [`m4`](https://github.com/Artfical/tpkg-m4) |
| Needs tOS build | 619 or newer |
| Size | 591636 bytes (1995621 unpacked) |
| SHA-256 of the `.tpkg` | `4bd6ce1296b0f113780dfc7172ac18fcf76b9ea93d6ee57935bff70e9b8d4ee5` |

## Commands it adds

| Command | Runs |
|---|---|
| `autoconf` | `bin/autoconf` |
| `autoheader` | `bin/autoheader` |
| `autom4te` | `bin/autom4te` |
| `autoreconf` | `bin/autoreconf` |
| `autoscan` | `bin/autoscan` |
| `autoupdate` | `bin/autoupdate` |
| `ifnames` | `bin/ifnames` |

## Download

The package file (`autoconf-2.72.tpkg`) and the sources it was built from are the assets of the
[v2.72 release](https://github.com/Artfical/tpkg-autoconf/releases/tag/v2.72).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `autoconf-2.72.tar.xz`

Check a download: `sha256sum autoconf-2.72.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: GPL-3.0-or-later. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
