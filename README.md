# tinygo

[中文版本](./README.cn.md)

Go compiler for small places. Microcontrollers, WebAssembly (WASM/WASI), and command-line tools. Based on LLVM.

![tinygo](https://repo.x-cmd.io/tinygo.svg)

## Install

```sh
x install tinygo
```

## Code insight

Total: **148,230** lines of code across **1879** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 132,723 | 39,628 | 23,304 | 1366 |
| LLVM | 4,372 | 387 | 934 | 60 |
| Json | 3,795 | 0 | 5 | 367 |
| AssemblyGAS | 3,133 | 1,257 | 605 | 78 |
| Makefile | 1,245 | 179 | 122 | 8 |

## OpenSSF Scorecard

Overall score: **5.7 / 10**

Lowest-scoring checks:

- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **Security-Policy** (0/10) — security policy file not detected

## Source

- **Upstream**: <https://github.com/tinygo-org/tinygo>
- **Homepage**: <https://tinygo.org>
- **License**: NOASSERTION

## Release

- **Latest**: `v0.42.0` (2026-09-01)
- **Last commit**: 2026-09-10
- **Assets in release**: 9

## Popularity

- **Stars**: 17,715 · **Forks**: 1,073 · **Open issues**: 1,844 · **Contributors**: 246

## Totals (cumulative)

- **Releases**: 52 · **Merged PRs**: 2978 · **Open PRs**: 127 · **Closed issues**: 1418 · **Open issues**: 426 · **Commits**: 4858

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 1 | 28 | 20 | 4 | 19 | 35 |
| last60d | 2026-07-12 | 1 | 63 | 28 | 10 | 28 | 92 |
| 90d | 2026-06-12 | 1 | 100 | 36 | 14 | 33 | 157 |
| last180d | 2026-03-14 | 3 | 231 | 49 | 39 | 50 | 344 |
| 360d | 2025-09-15 | 5 | 344 | 60 | 69 | 69 | 483 |
| last720d | 2024-09-20 | 11 | 620 | 83 | 185 | 142 | 890 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [tinygo0.42.0.darwin-amd64.tar.gz](https://github.com/tinygo-org/tinygo/releases/download/v0.42.0/tinygo0.42.0.darwin-amd64.tar.gz) | 157.9 MiB | `native/darwin/x64` |
| [tinygo0.42.0.darwin-arm64.tar.gz](https://github.com/tinygo-org/tinygo/releases/download/v0.42.0/tinygo0.42.0.darwin-arm64.tar.gz) | 155.5 MiB | `native/darwin/arm64` |
| [tinygo0.42.0.linux-amd64.tar.gz](https://github.com/tinygo-org/tinygo/releases/download/v0.42.0/tinygo0.42.0.linux-amd64.tar.gz) | 176.4 MiB | `native/linux/x64` |
| [tinygo0.42.0.linux-arm.tar.gz](https://github.com/tinygo-org/tinygo/releases/download/v0.42.0/tinygo0.42.0.linux-arm.tar.gz) | 169.0 MiB | `native/linux/arm` |
| [tinygo0.42.0.linux-arm64.tar.gz](https://github.com/tinygo-org/tinygo/releases/download/v0.42.0/tinygo0.42.0.linux-arm64.tar.gz) | 171.9 MiB | `native/linux/arm64` |
| [tinygo0.42.0.windows-amd64.zip](https://github.com/tinygo-org/tinygo/releases/download/v0.42.0/tinygo0.42.0.windows-amd64.zip) | 170.1 MiB | `native/win/x64` |
| [tinygo_0.42.0_amd64.deb](https://github.com/tinygo-org/tinygo/releases/download/v0.42.0/tinygo_0.42.0_amd64.deb) | 176.7 MiB | `runtime/deb/amd64` |
| [tinygo_0.42.0_arm64.deb](https://github.com/tinygo-org/tinygo/releases/download/v0.42.0/tinygo_0.42.0_arm64.deb) | 169.5 MiB | `runtime/deb/arm64` |
| [tinygo_0.42.0_armhf.deb](https://github.com/tinygo-org/tinygo/releases/download/v0.42.0/tinygo_0.42.0_armhf.deb) | 166.8 MiB | `runtime/deb/armhf` |

## Distribution status

Reported by **26** distros on [repology.org](https://repology.org/project/tinygo). **3** are ✅ on the latest upstream release, **21** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Arch | `0.41.1` | ⚠️ outdated |
| Fedora rawhide | `0.39.0` | ⚠️ outdated |
| Nix unstable | `0.41.1` | ⚠️ outdated |
| openSUSE Tumbleweed | `0.41.1` | ⚠️ outdated |

## Improve this data

Install metadata for tinygo lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `tinygo` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/tinygo.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260910.yml` · 2026-09-10T22:56:11Z._
