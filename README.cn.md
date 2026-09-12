# tinygo

[English version](./README.md)

Go compiler for small places. Microcontrollers, WebAssembly (WASM/WASI), and command-line tools. Based on LLVM.

![tinygo](https://repo.x-cmd.io/tinygo.svg?lang=zh)

## 安装

```sh
x install tinygo
```

## 代码洞察

合计: **148,391** 行代码（覆盖前 5 种语言、共 **1881** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 132,874 | 39,643 | 23,326 | 1367 |
| LLVM | 4,372 | 387 | 934 | 60 |
| Json | 3,803 | 0 | 5 | 368 |
| AssemblyGAS | 3,133 | 1,257 | 605 | 78 |
| Makefile | 1,247 | 179 | 122 | 8 |

## OpenSSF Scorecard 评分

总评分: **5.7 / 10**

评分最低的几项:

- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **Security-Policy** (0/10) — security policy file not detected

## 源代码

- **上游仓库**: <https://github.com/tinygo-org/tinygo>
- **官网**: <https://tinygo.org>
- **许可证**: NOASSERTION

## 发布

- **最新版本**: `v0.42.0` (2026-09-01)
- **最近提交**: 2026-09-11
- **Release 含资产**: 9 个

## 流行度

- **Star**: 17,721 · **Fork**: 1,074 · **开放 issue**: 1,845 · **贡献者**: 247

## 累计统计

- **发布数**: 52 · **已合并 PR**: 2981 · **开放 PR**: 130 · **已关闭 issue**: 1418 · **开放 issue**: 427 · **提交数**: 4861

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-13 | 1 | 28 | 24 | 3 | 18 | 37 |
| last60d | 2026-07-14 | 1 | 60 | 32 | 9 | 29 | 95 |
| 90d | 2026-06-14 | 1 | 103 | 38 | 14 | 34 | 160 |
| last180d | 2026-03-16 | 3 | 233 | 52 | 39 | 51 | 347 |
| 360d | 2025-09-17 | 5 | 346 | 63 | 69 | 70 | 486 |
| last720d | 2024-09-22 | 11 | 623 | 86 | 185 | 143 | 893 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [tinygo0.42.0.darwin-amd64.tar.gz](https://github.com/tinygo-org/tinygo/releases/download/v0.42.0/tinygo0.42.0.darwin-amd64.tar.gz) | 157.9 MiB | `native/darwin/x64` |
| [tinygo0.42.0.darwin-arm64.tar.gz](https://github.com/tinygo-org/tinygo/releases/download/v0.42.0/tinygo0.42.0.darwin-arm64.tar.gz) | 155.5 MiB | `native/darwin/arm64` |
| [tinygo0.42.0.linux-amd64.tar.gz](https://github.com/tinygo-org/tinygo/releases/download/v0.42.0/tinygo0.42.0.linux-amd64.tar.gz) | 176.4 MiB | `native/linux/x64` |
| [tinygo0.42.0.linux-arm.tar.gz](https://github.com/tinygo-org/tinygo/releases/download/v0.42.0/tinygo0.42.0.linux-arm.tar.gz) | 169.0 MiB | `native/linux/arm` |
| [tinygo0.42.0.linux-arm64.tar.gz](https://github.com/tinygo-org/tinygo/releases/download/v0.42.0/tinygo0.42.0.linux-arm64.tar.gz) | 171.9 MiB | `native/linux/arm64` |
| [tinygo0.42.0.windows-amd64.zip](https://github.com/tinygo-org/tinygo/releases/download/v0.42.0/tinygo0.42.0.windows-amd64.zip) | 170.1 MiB | `native/win/x64` |
| [tinygo_0.42.0_amd64.deb](https://github.com/tinygo-org/tinygo/releases/download/v0.42.0/tinygo_0.42.0_amd64.deb) | 176.7 MiB | `runtime/deb/amd64` |
| [tinygo_0.42.0_arm64.deb](https://github.com/tinygo-org/tinygo/releases/download/v0.42.0/tinygo_0.42.0_arm64.deb) | 169.5 MiB | `runtime/deb/arm64` |
| [tinygo_0.42.0_armhf.deb](https://github.com/tinygo-org/tinygo/releases/download/v0.42.0/tinygo_0.42.0_armhf.deb) | 166.8 MiB | `runtime/deb/armhf` |

## 发行版状态

在 [repology.org](https://repology.org/project/tinygo) 上共有 **26** 个发行版报告此项目。**3** 个 ✅ 已是最新上游版本，**21** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
| Arch | `0.41.1` | ⚠️ outdated |
| Fedora rawhide | `0.39.0` | ⚠️ outdated |
| Nix unstable | `0.41.1` | ⚠️ outdated |
| openSUSE Tumbleweed | `0.41.1` | ⚠️ outdated |

## 改进这些数据

tinygo 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `tinygo` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/tinygo.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260912.yml` · 2026-09-12T06:00:06Z._
