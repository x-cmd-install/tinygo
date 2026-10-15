# tinygo

[English version](./README.md)

Go compiler for small places. Microcontrollers, WebAssembly (WASM/WASI), and command-line tools. Based on LLVM.

[![x-cmd/install — tinygo Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/tinygo.svg?lang=zh)](https://x-cmd.com/install/tinygo)

## 安装

```sh
x install tinygo
```

## 代码洞察

合计: **161,523** 行代码（覆盖前 5 种语言、共 **1962** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 144,018 | 40,476 | 24,704 | 1435 |
| LLVM | 6,013 | 473 | 1,251 | 69 |
| Json | 3,869 | 0 | 5 | 372 |
| AssemblyGAS | 3,206 | 1,278 | 614 | 78 |
| Makefile | 1,315 | 173 | 131 | 8 |

## OpenSSF Scorecard 评分

总评分: **5.4 / 10**

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
- **最近提交**: 2026-10-14
- **Release 含资产**: 9 个

## 流行度

- **Star**: 17,815 · **Fork**: 1,089 · **开放 issue**: 1,908 · **贡献者**: 249

## 累计统计

- **发布数**: 53 · **已合并 PR**: 3092 · **开放 PR**: 127 · **已关闭 issue**: 1465 · **开放 issue**: 443 · **提交数**: 5013

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-09-15 | 1 | 89 | 38 | 15 | 45 | 117 |
| last60d | 2026-08-16 | 2 | 129 | 43 | 28 | 56 | 172 |
| 90d | 2026-07-17 | 2 | 167 | 49 | 35 | 63 | 234 |
| last180d | 2026-04-18 | 4 | 294 | 61 | 68 | 76 | 419 |
| 360d | 2025-10-20 | 6 | 441 | 72 | 103 | 94 | 620 |
| last720d | 2024-10-25 | 12 | 697 | 90 | 208 | 158 | 995 |

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

_数据快照: `data/card/261015.yml` · 2026-10-15T05:45:02Z._
