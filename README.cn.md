# tinygo

[English version](./README.md)

Go compiler for small places. Microcontrollers, WebAssembly (WASM/WASI), and command-line tools. Based on LLVM.

[![x-cmd/install — tinygo Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/tinygo.svg?lang=zh)](https://x-cmd.com/install/tinygo)

## 安装

```sh
x install tinygo
```

## 代码洞察

合计: **195,900** 行代码（覆盖前 5 种语言、共 **2245** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 174,216 | 40,802 | 27,879 | 1661 |
| LLVM | 9,445 | 603 | 1,808 | 101 |
| Json | 4,027 | 0 | 5 | 394 |
| AssemblyGAS | 3,438 | 1,379 | 651 | 81 |
| Makefile | 1,393 | 182 | 134 | 8 |

## OpenSSF Scorecard 评分

总评分: **5.8 / 10**

评分最低的几项:

- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected
- **Security-Policy** (0/10) — security policy file not detected

## 源代码

- **上游仓库**: <https://github.com/tinygo-org/tinygo>
- **官网**: <https://tinygo.org>
- **许可证**: NOASSERTION

## 发布

- **最新版本**: `v0.44.0` (2026-10-28)
- **最近提交**: 2026-11-21
- **Release 含资产**: 9 个

## 流行度

- **Star**: 17,924 · **Fork**: 1,114 · **开放 issue**: 2,014 · **贡献者**: 262

## 累计统计

- **发布数**: 54 · **已合并 PR**: 3470 · **开放 PR**: 147 · **已关闭 issue**: 1641 · **开放 issue**: 373 · **提交数**: 5485

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-10-22 | 1 | 289 | 66 | 17 | 55 | 313 |
| last60d | 2026-09-22 | 2 | 443 | 79 | 59 | 99 | 525 |
| 90d | 2026-08-23 | 3 | 501 | 85 | 80 | 107 | 638 |
| last180d | 2026-05-25 | 3 | 618 | 93 | 104 | 122 | 833 |
| 360d | 2025-11-26 | 7 | 806 | 103 | 159 | 136 | 1078 |
| last720d | 2024-12-01 | 12 | 1020 | 113 | 266 | 177 | 1403 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [tinygo0.44.0.darwin-amd64.tar.gz](https://github.com/tinygo-org/tinygo/releases/download/v0.44.0/tinygo0.44.0.darwin-amd64.tar.gz) | 159.8 MiB | `native/darwin/x64` |
| [tinygo0.44.0.darwin-arm64.tar.gz](https://github.com/tinygo-org/tinygo/releases/download/v0.44.0/tinygo0.44.0.darwin-arm64.tar.gz) | 157.1 MiB | `native/darwin/arm64` |
| [tinygo0.44.0.linux-amd64.tar.gz](https://github.com/tinygo-org/tinygo/releases/download/v0.44.0/tinygo0.44.0.linux-amd64.tar.gz) | 179.6 MiB | `native/linux/x64` |
| [tinygo0.44.0.linux-arm.tar.gz](https://github.com/tinygo-org/tinygo/releases/download/v0.44.0/tinygo0.44.0.linux-arm.tar.gz) | 171.5 MiB | `native/linux/arm` |
| [tinygo0.44.0.linux-arm64.tar.gz](https://github.com/tinygo-org/tinygo/releases/download/v0.44.0/tinygo0.44.0.linux-arm64.tar.gz) | 174.4 MiB | `native/linux/arm64` |
| [tinygo0.44.0.windows-amd64.zip](https://github.com/tinygo-org/tinygo/releases/download/v0.44.0/tinygo0.44.0.windows-amd64.zip) | 171.9 MiB | `native/win/x64` |
| [tinygo_0.44.0_amd64.deb](https://github.com/tinygo-org/tinygo/releases/download/v0.44.0/tinygo_0.44.0_amd64.deb) | 179.9 MiB | `runtime/deb/amd64` |
| [tinygo_0.44.0_arm64.deb](https://github.com/tinygo-org/tinygo/releases/download/v0.44.0/tinygo_0.44.0_arm64.deb) | 172.2 MiB | `runtime/deb/arm64` |
| [tinygo_0.44.0_armhf.deb](https://github.com/tinygo-org/tinygo/releases/download/v0.44.0/tinygo_0.44.0_armhf.deb) | 169.2 MiB | `runtime/deb/armhf` |

## 发行版状态

在 [repology.org](https://repology.org/project/tinygo) 上共有 **27** 个发行版报告此项目。**4** 个 ✅ 已是最新上游版本，**21** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
| Arch | `0.43.0` | ⚠️ outdated |
| Fedora rawhide | `0.39.0` | ⚠️ outdated |
| Nix unstable | `0.44.0` | ✅ latest |
| openSUSE Tumbleweed | `0.43.0` | ⚠️ outdated |

## 改进这些数据

tinygo 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `tinygo` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/tinygo.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/261121.yml` · 2026-11-21T08:51:44Z._
