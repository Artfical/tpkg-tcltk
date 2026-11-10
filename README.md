# tcltk

Tcl and Tk 8.6.16: tclsh, wish (the Tk windowing shell for X), and the libraries Python's tkinter uses

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install tcltk
```

| | |
|---|---|
| Version | 8.6.16 |
| Licence | TCL (BSD-style) |
| Upstream | https://www.tcl-lang.org |
| Needs | [`xorg`](https://github.com/Artfical/tpkg-xorg), [`zlib`](https://github.com/Artfical/tpkg-zlib) |
| Needs tOS build | 618 or newer |
| Size | 2546644 bytes (7232696 unpacked) |
| SHA-256 of the `.tpkg` | `0286d4b540e3467142735f613733ba7ee743db5268503164335e54712e46ac83` |

## Commands it adds

| Command | Runs |
|---|---|
| `tclsh` | `bin/tclsh8.6` |
| `wish` | `bin/wish8.6` |

## Download

The package file (`tcltk-8.6.16.tpkg`) and the sources it was built from are the assets of the
[v8.6.16 release](https://github.com/Artfical/tpkg-tcltk/releases/tag/v8.6.16).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `tcl8.6.16-src.tar.gz`
- `tk8.6.16-src.tar.gz`

Check a download: `sha256sum tcltk-8.6.16.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: TCL (BSD-style). The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
