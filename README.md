# tinygo

[中文版本](./README.cn.md)

Go compiler for small places. Microcontrollers, WebAssembly (WASM/WASI), and command-line tools. Based on LLVM.

[![x-cmd/install — tinygo Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/tinygo.svg)](https://x-cmd.com/install/tinygo)

## Install

```sh
x install tinygo
```

## Code insight

Total: **157,291** lines of code across **1943** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 140,146 | 40,488 | 24,301 | 1418 |
| LLVM | 5,694 | 467 | 1,202 | 67 |
| Json | 3,868 | 0 | 5 | 372 |
| AssemblyGAS | 3,206 | 1,278 | 614 | 78 |
| Makefile | 1,296 | 175 | 126 | 8 |

## OpenSSF Scorecard

Overall score: **5.8 / 10**

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
- **Last commit**: 2026-09-29
- **Assets in release**: 9

## Popularity

- **Stars**: 17,797 · **Forks**: 1,080 · **Open issues**: 1,870 · **Contributors**: 249

## Totals (cumulative)

- **Releases**: 52 · **Merged PRs**: 3055 · **Open PRs**: 106 · **Closed issues**: 1445 · **Open issues**: 425 · **Commits**: 4963

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-30 | 1 | 76 | 17 | 11 | 24 | 94 |
| last60d | 2026-07-31 | 1 | 109 | 20 | 22 | 32 | 148 |
| 90d | 2026-07-01 | 1 | 160 | 31 | 30 | 38 | 238 |
| last180d | 2026-04-02 | 3 | 291 | 38 | 58 | 52 | 415 |
| 360d | 2025-10-04 | 5 | 409 | 50 | 91 | 71 | 575 |
| last720d | 2024-10-09 | 11 | 684 | 68 | 200 | 139 | 977 |

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

_Snapshot: `data/card/260929.yml` · 2026-09-29T07:09:48Z._
