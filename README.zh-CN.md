# DriveMind

![DriveMind lockup](assets/logo/drivemind-lockup.svg)

[English](./README.md) · [简体中文](./README.zh-CN.md) · [GitHub 仓库](https://github.com/Yuzc-001/DriveMind) · [Issues](https://github.com/Yuzc-001/DriveMind/issues)

[![Version](https://img.shields.io/badge/version-v0.6.0-0B1738?style=flat-square)](./CHANGELOG.md)
[![License](https://img.shields.io/badge/license-BUSL--1.1-23C993?style=flat-square)](./LICENSE.md)
[![Type](https://img.shields.io/badge/type-execution--integrity-5B6CFF?style=flat-square)](./skill/SKILL.md)
[![Codex](https://img.shields.io/badge/install-codex-29A8D8?style=flat-square)](./docs/installation.md)
[![Claude%20Code](https://img.shields.io/badge/install-claude%20code-4466F2?style=flat-square)](./docs/installation.md)

> **一层面向长程人机协作的执行完整性层。**
>
> 防止有意义的工作在时间、压力和上下文边界中退化，并把真实工作沉淀成更强的未来默认。

DriveMind 不应再主要被理解为一个“温柔、理性的可靠性层”。
那个方向是对的，但对真正的作品来说还不够硬。

`DriveMind v0.6` 现在更准确的定位是：

# 在长任务里保持人机协作不退化、可恢复、可沉淀的执行层

**当前版本：** `v0.6.0`

---

## DriveMind 现在是什么

DriveMind 现在围绕两件事展开：

# 执行完整性
# 经验复利

这意味着它主要在对抗长任务中的五种退化：
1. 目标漂移
2. 边界漂移
3. 连续性衰减
4. 卡住后的假忙退化
5. 收口失败

如果它不能把这些退化压下去，它就还不够像一个真正的作品。

---

## 为什么需要 DriveMind

有意义的人机协作，很多时候不是突然失败，
而是逐步退化：

- 目标慢慢变糊
- 压力慢慢侵蚀边界
- 中断慢慢损坏连续性
- 卡住后动作越来越多，但判断越来越差
- 做完之后没有留下任何能让下一次更强的东西

DriveMind 的作用，就是对抗这种退化。
同时，当任务本身值得时，它还要把任务留下的 residue 变成未来的复利：
- lesson
- next-time rule
- handoff state
- memory
- review residue

---

## 这个仓库现在提供什么

DriveMind `v0.6.0` 当前包含：
- `skill/SKILL.md` 中的 DriveMind skill 本体
- `skill/references/` 下新的核心骨架：
  - `drift-prevention.md`
  - `boundary-preservation.md`
  - `continuity-preservation.md`
  - `stuck-recovery.md`
  - `closure-compounding.md`
- 一批兼容型旧 references，用来把旧结构导向新结构
- `skill/templates/` 下的 diary / review / distill 模板
- `scripts/` 下的安装与 bootstrap 脚本
- `docs/` 下的产品、安装、许可和支撑文档
- `examples/` 下的示例与演示
- `assets/` 下的品牌与仓库展示资产

---

## v0.6 到底变了什么

`v0.6` 不是把旧 doctrine 再讲得更成熟一点。
而是一次产品中心重构：

# 它现在被定义为：
# 让有意义的工作保持对齐、守住边界、可恢复，并且能留下更强未来默认的层。

所以现在 DriveMind 不再主要按“气质是否成熟”来判断，
而要按：

# 它有没有真正减少长任务中的退化

来判断。

---

## 基本启用方式

例如：
- `Use DriveMind here. Keep the thread stable.`
- `This may drift if we keep going. Enable DriveMind.`
- `Stay with this, but ask before crossing a risky boundary.`
- `We may continue tomorrow. Preserve continuity.`
- `Review this afterward and leave behind a next-time rule.`

当 DriveMind 激活时，真正的问题不再是“怎么显得更稳重”，
而是：

# 如果没有 DriveMind discipline，这项工作最可能在哪个维度退化？

---

## 仓库结构

- `skill/SKILL.md` — runtime skill 本体
- `skill/references/` — 执行完整性与经验复利 references
- `skill/templates/` — diary / review / distill 模板
- `docs/drivemind-v0.6-product-thesis.md` — 新的 v0.6 产品中轴
- `docs/installation.md` — 安装与 bootstrap 说明
- `docs/use-cases.md` / `docs/with-vs-without.md` — 示例与对比
- `CHANGELOG.md` / `VERSION` — 版本历史与当前版本
- `examples/` — 演练示例与 walkthroughs

---

## 它不是什么

DriveMind 不是：
- 面向所有 agent 的泛成熟升级包
- 一层广义的协作礼仪系统
- 单独的 diary 工具
- 单独的 memory plugin
- 一张“可以更莽地推进”的通行证

它是一层执行完整性层，目标是让人机协作：
- 更不容易跑偏
- 更不容易越界
- 更容易恢复
- 更容易留下可复用的未来默认

---

## 安装

详见 [docs/installation.md](docs/installation.md)。

当前提供 Claude Code 和 Codex 的安装流，也验证了 OpenClaw 风格的 skill-hosted 工作流。

---

## 继续阅读

- [README.md](README.md)
- [CHANGELOG.md](CHANGELOG.md)
- [skill/SKILL.md](skill/SKILL.md)
- [docs/drivemind-v0.6-product-thesis.md](docs/drivemind-v0.6-product-thesis.md)
- [docs/installation.md](docs/installation.md)
- [docs/use-cases.md](docs/use-cases.md)
- [docs/with-vs-without.md](docs/with-vs-without.md)
- [docs/github-release-v0.6.0.md](docs/github-release-v0.6.0.md)
- [docs/github-release-v0.5.0.md](docs/github-release-v0.5.0.md)

---

## 协作与沟通

- Issues：https://github.com/Yuzc-001/DriveMind/issues
- 邮箱：`zxyu24@outlook.com`

适合公开讨论的 bug、安装问题、文档缺口、功能建议，请优先走 Issues。
涉及许可、私下协作、或不适合在公开线程中开始的问题，可以直接发邮件。
