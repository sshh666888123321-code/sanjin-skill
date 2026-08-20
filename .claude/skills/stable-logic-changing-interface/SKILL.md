---
name: stable-logic-changing-interface
description: |
  Use when a fast-changing AI tool or platform改版、换入口、换按钮，团队纠结是否重学全部工具；触发信号包括“工具又更新了”“这个按钮在哪”“底层逻辑是什么”。不适用于单纯排查一个具体软件故障，或需要比较当前工具价格与功能的采购决策。
source_book: 《叁斤全部帖子》 叁斤
source_chapter: 038、039、006、060、064
tags: [ai, invariants, tool-selection, transfer]
related_skills:
  - slug: element-level-benchmarking-hotspot-lifecycle
    relation: contrasts-with
  - slug: manual-before-automation
    relation: composes-with

---

# 不变逻辑—变化界面二层判断

## R — 原文 (Reading)

> AI交互的底层逻辑，本质上就是你能不能把你的需求、背景情况、以及想让AI完成的具体任务，清晰、准确地描述给它听。
>
> — 叁斤，038｜底层逻辑

## I — 方法论骨架 (Interpretation)

任何快速变化的工具都可以拆成两层。
稳定层是用户问题、输入背景、约束、验收标准和因果关系；界面层是按钮、入口、模型名称、平台规则和操作路径。
遇到改版时，先保留稳定层的任务定义，不要把旧界面误当成能力本身。
只重新确认新入口如何承载同一任务，以及哪些限制发生了变化。
这样学习投入服务于真实工作，不会被“追最新工具”拖走。

## A1 — 书中的应用 (Past Application)

### 案例 1: AI 工具选型
- **问题**: 飞书知识库、IMA、NotebookLM 等工具用起来不顺。
- **方法论的使用**: 先按本地文件、可调用、可执行任务等稳定需求试用工具，再选择 Obsidian + Claude Code。
- **结论**: 工具不是目的，能否承载真实任务才是判断标准。
- **结果**: 形成可执行内容、产品和知识维护的本地 AI 知识库（c07）。

### 案例 2: 跨平台复制
- **问题**: 同一涨粉接单模式在不同平台表现不一致。
- **方法论的使用**: 保留用户需求与成交逻辑，重新验证平台界面、分发和规则。
- **结论**: 稳定逻辑可以迁移，操作路径和结果不能直接照搬。
- **结果**: 得物方向有反馈，小红书千粉商单失败（c29）。

## A2 — 触发场景 (Future Trigger) ★

### 用户会在什么情境下需要这个 skill?

1. AI 产品或平台突然改版，用户担心原方法全部失效。
2. 团队把大量时间花在学按钮、追模型，却说不清实际任务。
3. 需要把一个已验证的工作方法迁移到新工具或新平台。

### 语言信号

- “工具更新后我是不是要从头学？” / “Should I relearn everything after the update?”
- “这个功能下线了，但我的目标不变，怎么办？”
- “底层逻辑和表面操作怎么区分？”

### 与相邻 skill 的区分

- 与 `manual-before-automation` 的区别：本 skill 分离稳定逻辑与界面；后者要求先手动跑通流程。
- 与 `contextual-precision-questioning` 的区别：本 skill 判断迁移层级；后者具体补齐一次提问所缺的信息。

## E — 可执行步骤 (Execution)

1. **写出不变量**：用一句话说明目标、输入、约束和验收结果。完成标准：不提任何具体按钮或品牌仍能执行。
2. **标出变化界面**：记录新旧入口、功能限制、平台分发和权限差异。完成标准：每项差异都有验证来源或实际试用结果。
3. **最小迁移测试**：用一份真实任务在新界面跑通，并比较输出是否达到原验收标准。完成标准：保留差异清单，只有变化层需要补学。

## B — 边界 (Boundary) ★

### 不要在以下情况使用此 skill

- 需要实时比较软件价格、套餐或合规条款。
- 只是一个具体按钮报错，且稳定任务逻辑没有变化。

### 作者在书中警告的失败模式

- 只看平台或工具热度就迁移，忽略人群、规则和能力差异（c29）。
- 把功能名和操作路径当作方法本身，工具一变就全部失去方向。

### 作者的盲点 / 时代局限

- 有些平台政策变化会直接改变可行性；“逻辑不变”不能替代最新的权限、隐私和规则核验。

### 容易混淆的邻近方法论

- `manual-before-automation`、`contextual-precision-questioning`。

## 相关 skills

- `element-level-benchmarking-hotspot-lifecycle` — contrasts-with
- `manual-before-automation` — composes-with

## 审计信息

- **验证通过**: V1 ✓ / V2 ✓ / V3 ✓
- **测试通过率**: 6/6（100%，保守自测；待独立盲测）
- **蒸馏时间**: 2026-08-20


