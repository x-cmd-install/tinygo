# tinygo

[中文版本](./README.cn.md)

Go compiler for small places. Microcontrollers, WebAssembly (WASM/WASI), and command-line tools. Based on LLVM.

![tinygo](https://repo.x-cmd.io/tinygo.svg)

## Install

```sh
x install tinygo
```

## Code insight

Total: **150,715** lines of code across **1903** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 134,868 | 39,809 | 23,588 | 1385 |
| LLVM | 4,626 | 397 | 1,011 | 62 |
| Json | 3,827 | 0 | 5 | 370 |
| AssemblyGAS | 3,179 | 1,265 | 612 | 78 |
| Makefile | 1,261 | 172 | 125 | 8 |

## OpenSSF Scorecard

Overall score: **5.6 / 10**

Lowest-scoring checks:

- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected
- **Security-Policy** (0/10) — security policy file not detected

## Source

- **Upstream**: <https://github.com/tinygo-org/tinygo>
- **Homepage**: <https://tinygo.org>
- **License**: NOASSERTION

## Release

- **Latest**: `v0.42.0` (2026-09-01)
- **Last commit**: 2026-09-16
- **Assets in release**: 9

## Popularity

- **Stars**: 17,733 · **Forks**: 1,075 · **Open issues**: 1,849 · **Contributors**: 247

## Totals (cumulative)

- **Releases**: 52 · **Merged PRs**: 2993 · **Open PRs**: 117 · **Closed issues**: 1423 · **Open issues**: 426 · **Commits**: 4883

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-18 | 1 | 33 | 17 | 7 | 17 | 40 |
| last60d | 2026-07-19 | 1 | 68 | 25 | 12 | 27 | 101 |
| 90d | 2026-06-19 | 1 | 111 | 32 | 16 | 33 | 178 |
| last180d | 2026-03-21 | 3 | 240 | 46 | 42 | 50 | 356 |
| 360d | 2025-09-22 | 5 | 352 | 57 | 73 | 70 | 500 |
| last720d | 2024-09-27 | 11 | 635 | 77 | 186 | 143 | 913 |

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

## Improve this data

Install metadata for tinygo lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `tinygo` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/tinygo.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260917.yml` · 2026-09-17T06:33:21Z._
