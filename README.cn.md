# tinygo

[English version](./README.md)

Go compiler for small places. Microcontrollers, WebAssembly (WASM/WASI), and command-line tools. Based on LLVM.

[![x-cmd/install — tinygo Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/tinygo.svg?lang=zh)](https://x-cmd.com/install/tinygo)

## 安装

```sh
x install tinygo
```

## 代码洞察

合计: **167,444** 行代码（覆盖前 5 种语言、共 **2021** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 148,610 | 41,051 | 25,307 | 1482 |
| LLVM | 7,163 | 513 | 1,417 | 75 |
| Json | 3,928 | 0 | 5 | 378 |
| AssemblyGAS | 3,278 | 1,291 | 623 | 78 |
| Makefile | 1,347 | 175 | 132 | 8 |

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

- **最新版本**: `v0.43.0` (2026-10-09)
- **最近提交**: 2026-10-24
- **Release 含资产**: 9 个

## 流行度

- **Star**: 17,841 · **Fork**: 1,092 · **开放 issue**: 1,947 · **贡献者**: 251

## 累计统计

- **发布数**: 53 · **已合并 PR**: 3157 · **开放 PR**: 140 · **已关闭 issue**: 1479 · **开放 issue**: 468 · **提交数**: 5108

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-09-24 | 1 | 118 | 50 | 23 | 65 | 169 |
| last60d | 2026-08-25 | 2 | 187 | 60 | 37 | 81 | 257 |
| 90d | 2026-07-26 | 2 | 216 | 62 | 45 | 87 | 306 |
| last180d | 2026-04-27 | 2 | 346 | 73 | 75 | 101 | 501 |
| 360d | 2025-10-29 | 6 | 504 | 85 | 115 | 120 | 713 |
| last720d | 2024-11-03 | 11 | 742 | 102 | 213 | 184 | 1075 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [tinygo0.43.0.darwin-amd64.tar.gz](https://github.com/tinygo-org/tinygo/releases/download/v0.43.0/tinygo0.43.0.darwin-amd64.tar.gz) | 158.3 MiB | `native/darwin/x64` |
| [tinygo0.43.0.darwin-arm64.tar.gz](https://github.com/tinygo-org/tinygo/releases/download/v0.43.0/tinygo0.43.0.darwin-arm64.tar.gz) | 155.9 MiB | `native/darwin/arm64` |
| [tinygo0.43.0.linux-amd64.tar.gz](https://github.com/tinygo-org/tinygo/releases/download/v0.43.0/tinygo0.43.0.linux-amd64.tar.gz) | 178.1 MiB | `native/linux/x64` |
| [tinygo0.43.0.linux-arm.tar.gz](https://github.com/tinygo-org/tinygo/releases/download/v0.43.0/tinygo0.43.0.linux-arm.tar.gz) | 170.2 MiB | `native/linux/arm` |
| [tinygo0.43.0.linux-arm64.tar.gz](https://github.com/tinygo-org/tinygo/releases/download/v0.43.0/tinygo0.43.0.linux-arm64.tar.gz) | 173.2 MiB | `native/linux/arm64` |
| [tinygo0.43.0.windows-amd64.zip](https://github.com/tinygo-org/tinygo/releases/download/v0.43.0/tinygo0.43.0.windows-amd64.zip) | 170.6 MiB | `native/win/x64` |
| [tinygo_0.43.0_amd64.deb](https://github.com/tinygo-org/tinygo/releases/download/v0.43.0/tinygo_0.43.0_amd64.deb) | 178.5 MiB | `runtime/deb/amd64` |
| [tinygo_0.43.0_arm64.deb](https://github.com/tinygo-org/tinygo/releases/download/v0.43.0/tinygo_0.43.0_arm64.deb) | 170.9 MiB | `runtime/deb/arm64` |
| [tinygo_0.43.0_armhf.deb](https://github.com/tinygo-org/tinygo/releases/download/v0.43.0/tinygo_0.43.0_armhf.deb) | 167.9 MiB | `runtime/deb/armhf` |

## 发行版状态

在 [repology.org](https://repology.org/project/tinygo) 上共有 **26** 个发行版报告此项目。**7** 个 ✅ 已是最新上游版本，**17** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
| Arch | `0.43.0` | ✅ latest |
| Fedora rawhide | `0.39.0` | ⚠️ outdated |
| Nix unstable | `0.43.0` | ✅ latest |
| openSUSE Tumbleweed | `0.41.1` | ⚠️ outdated |

## 改进这些数据

tinygo 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `tinygo` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/tinygo.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/261024.yml` · 2026-10-24T05:48:09Z._
