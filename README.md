# tinygo

[中文版本](./README.cn.md)

Go compiler for small places. Microcontrollers, WebAssembly (WASM/WASI), and command-line tools. Based on LLVM.

[![x-cmd/install — tinygo Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/tinygo.svg)](https://x-cmd.com/install/tinygo)

## Install

```sh
x install tinygo
```

## Code insight

Total: **171,853** lines of code across **2051** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 152,792 | 41,288 | 25,652 | 1512 |
| LLVM | 7,319 | 519 | 1,443 | 75 |
| Json | 3,930 | 0 | 5 | 378 |
| AssemblyGAS | 3,322 | 1,292 | 626 | 78 |
| Makefile | 1,360 | 175 | 132 | 8 |

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

- **Latest**: `v0.44.0` (2026-10-28)
- **Last commit**: 2026-11-01
- **Assets in release**: 9

## Popularity

- **Stars**: 17,874 · **Forks**: 1,098 · **Open issues**: 1,970 · **Contributors**: 257

## Totals (cumulative)

- **Releases**: 54 · **Merged PRs**: 3203 · **Open PRs**: 168 · **Closed issues**: 1593 · **Open issues**: 377 · **Commits**: 5163

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-10-02 | 2 | 119 | 89 | 21 | 70 | 137 |
| last60d | 2026-09-02 | 2 | 217 | 100 | 46 | 85 | 288 |
| 90d | 2026-08-03 | 3 | 254 | 102 | 62 | 91 | 335 |
| last180d | 2026-05-05 | 3 | 385 | 115 | 88 | 104 | 536 |
| 360d | 2025-11-06 | 7 | 547 | 124 | 136 | 121 | 762 |
| last720d | 2024-11-11 | 12 | 786 | 135 | 241 | 172 | 1123 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [tinygo0.44.0.darwin-amd64.tar.gz](https://github.com/tinygo-org/tinygo/releases/download/v0.44.0/tinygo0.44.0.darwin-amd64.tar.gz) | 159.8 MiB | `native/darwin/x64` |
| [tinygo0.44.0.darwin-arm64.tar.gz](https://github.com/tinygo-org/tinygo/releases/download/v0.44.0/tinygo0.44.0.darwin-arm64.tar.gz) | 157.1 MiB | `native/darwin/arm64` |
| [tinygo0.44.0.linux-amd64.tar.gz](https://github.com/tinygo-org/tinygo/releases/download/v0.44.0/tinygo0.44.0.linux-amd64.tar.gz) | 179.6 MiB | `native/linux/x64` |
| [tinygo0.44.0.linux-arm.tar.gz](https://github.com/tinygo-org/tinygo/releases/download/v0.44.0/tinygo0.44.0.linux-arm.tar.gz) | 171.5 MiB | `native/linux/arm` |
| [tinygo0.44.0.linux-arm64.tar.gz](https://github.com/tinygo-org/tinygo/releases/download/v0.44.0/tinygo0.44.0.linux-arm64.tar.gz) | 174.4 MiB | `native/linux/arm64` |
| [tinygo0.44.0.windows-amd64.zip](https://github.com/tinygo-org/tinygo/releases/download/v0.44.0/tinygo0.44.0.windows-amd64.zip) | 171.9 MiB | `native/win/x64` |
| [tinygo_0.44.0_amd64.deb](https://github.com/tinygo-org/tinygo/releases/download/v0.44.0/tinygo_0.44.0_amd64.deb) | 179.9 MiB | `runtime/deb/amd64` |
| [tinygo_0.44.0_arm64.deb](https://github.com/tinygo-org/tinygo/releases/download/v0.44.0/tinygo_0.44.0_arm64.deb) | 172.2 MiB | `runtime/deb/arm64` |
| [tinygo_0.44.0_armhf.deb](https://github.com/tinygo-org/tinygo/releases/download/v0.44.0/tinygo_0.44.0_armhf.deb) | 169.2 MiB | `runtime/deb/armhf` |

## Distribution status

Reported by **26** distros on [repology.org](https://repology.org/project/tinygo). **3** are ✅ on the latest upstream release, **21** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Arch | `0.43.0` | ⚠️ outdated |
| Fedora rawhide | `0.39.0` | ⚠️ outdated |
| Nix unstable | `0.43.0` | ⚠️ outdated |
| openSUSE Tumbleweed | `0.41.1` | ⚠️ outdated |

## Improve this data

Install metadata for tinygo lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `tinygo` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/tinygo.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/261101.yml` · 2026-11-01T07:17:31Z._
