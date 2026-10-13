# tinygo

[English version](./README.md)

Go compiler for small places. Microcontrollers, WebAssembly (WASM/WASI), and command-line tools. Based on LLVM.

[![x-cmd/install — tinygo Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/tinygo.svg?lang=zh)](https://x-cmd.com/install/tinygo)

## 安装

```sh
x install tinygo
```

## 代码洞察

合计: **161,397** 行代码（覆盖前 5 种语言、共 **1961** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 143,918 | 40,483 | 24,698 | 1435 |
| LLVM | 5,987 | 472 | 1,247 | 68 |
| Json | 3,869 | 0 | 5 | 372 |
| AssemblyGAS | 3,206 | 1,278 | 614 | 78 |
| Makefile | 1,315 | 173 | 131 | 8 |

## OpenSSF Scorecard 评分

总评分: **5.5 / 10**

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
- **最近提交**: 2026-10-12
- **Release 含资产**: 9 个

## 流行度

- **Star**: 17,810 · **Fork**: 1,087 · **开放 issue**: 1,905 · **贡献者**: 249

## 累计统计

- **发布数**: 53 · **已合并 PR**: 3086 · **开放 PR**: 118 · **已关闭 issue**: 1462 · **开放 issue**: 443 · **提交数**: 5007

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-09-13 | 1 | 86 | 29 | 13 | 45 | 111 |
| last60d | 2026-08-14 | 2 | 125 | 34 | 25 | 56 | 166 |
| 90d | 2026-07-15 | 2 | 161 | 40 | 33 | 64 | 228 |
| last180d | 2026-04-16 | 4 | 298 | 52 | 65 | 76 | 413 |
| 360d | 2025-10-18 | 6 | 435 | 63 | 100 | 94 | 614 |
| last720d | 2024-10-23 | 12 | 697 | 81 | 206 | 159 | 992 |

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

## 改进这些数据

tinygo 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `tinygo` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/tinygo.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/261013.yml` · 2026-10-13T08:05:37Z._
