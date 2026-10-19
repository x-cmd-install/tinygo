# tinygo

[中文版本](./README.cn.md)

Go compiler for small places. Microcontrollers, WebAssembly (WASM/WASI), and command-line tools. Based on LLVM.

[![x-cmd/install — tinygo Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/tinygo.svg)](https://x-cmd.com/install/tinygo)

## Install

```sh
x install tinygo
```

## Code insight

Total: **162,529** lines of code across **1973** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 144,904 | 40,591 | 24,840 | 1446 |
| LLVM | 6,053 | 476 | 1,256 | 69 |
| Json | 3,870 | 0 | 5 | 372 |
| AssemblyGAS | 3,279 | 1,296 | 625 | 78 |
| Makefile | 1,321 | 173 | 130 | 8 |

## OpenSSF Scorecard

Overall score: **5.4 / 10**

Lowest-scoring checks:

- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected
- **Security-Policy** (0/10) — security policy file not detected

## Source

- **Upstream**: <https://github.com/tinygo-org/tinygo>
- **Homepage**: <https://tinygo.org>
- **License**: NOASSERTION

## Release

- **Latest**: `v0.43.0` (2026-10-09)
- **Last commit**: 2026-10-18
- **Assets in release**: 9

## Popularity

- **Stars**: 17,823 · **Forks**: 1,092 · **Open issues**: 1,914 · **Contributors**: 249

## Totals (cumulative)

- **Releases**: 53 · **Merged PRs**: 3108 · **Open PRs**: 137 · **Closed issues**: 1470 · **Open issues**: 444 · **Commits**: 5032

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-09-19 | 1 | 94 | 44 | 15 | 42 | 0 |
| last60d | 2026-08-20 | 2 | 141 | 53 | 31 | 57 | 0 |
| 90d | 2026-07-21 | 2 | 178 | 59 | 38 | 64 | 0 |
| last180d | 2026-04-22 | 3 | 301 | 70 | 69 | 77 | 0 |
| 360d | 2025-10-24 | 6 | 456 | 82 | 107 | 95 | 0 |
| last720d | 2024-10-29 | 11 | 705 | 100 | 208 | 159 | 1006 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [tinygo0.43.0.darwin-amd64.tar.gz](https://github.com/tinygo-org/tinygo/releases/download/v0.43.0/tinygo0.43.0.darwin-amd64.tar.gz) | 158.3 MiB | `native/darwin/x64` |
| [tinygo0.43.0.darwin-arm64.tar.gz](https://github.com/tinygo-org/tinygo/releases/download/v0.43.0/tinygo0.43.0.darwin-arm64.tar.gz) | 155.9 MiB | `native/darwin/arm64` |
| [tinygo0.43.0.linux-amd64.tar.gz](https://github.com/tinygo-org/tinygo/releases/download/v0.43.0/tinygo0.43.0.linux-amd64.tar.gz) | 178.1 MiB | `native/linux/x64` |
| [tinygo0.43.0.linux-arm.tar.gz](https://github.com/tinygo-org/tinygo/releases/download/v0.43.0/tinygo0.43.0.linux-arm.tar.gz) | 170.2 MiB | `native/linux/arm` |
| [tinygo0.43.0.linux-arm64.tar.gz](https://github.com/tinygo-org/tinygo/releases/download/v0.43.0/tinygo0.43.0.linux-arm64.tar.gz) | 173.2 MiB | `native/linux/arm64` |
| [tinygo0.43.0.windows-amd64.zip](https://github.com/tinygo-org/tinygo/releases/download/v0.43.0/tinygo0.43.0.windows-amd64.zip) | 170.6 MiB | `native/win/x64` |
| [tinygo_0.43.0_amd64.deb](https://github.com/tinygo-org/tinygo/releases/download/v0.43.0/tinygo_0.43.0_amd64.deb) | 178.5 MiB | `runtime/deb/amd64` |
| [tinygo_0.43.0_arm64.deb](https://github.com/tinygo-org/tinygo/releases/download/v0.43.0/tinygo_0.43.0_arm64.deb) | 170.9 MiB | `runtime/deb/arm64` |
| [tinygo_0.43.0_armhf.deb](https://github.com/tinygo-org/tinygo/releases/download/v0.43.0/tinygo_0.43.0_armhf.deb) | 167.9 MiB | `runtime/deb/armhf` |

## Improve this data

Install metadata for tinygo lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `tinygo` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/tinygo.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/261019.yml` · 2026-10-19T05:44:59Z._
