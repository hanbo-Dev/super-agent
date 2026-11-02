# Contributing

本仓库由代理（agent）协助开发。本文说明如何向代理提需求、代理的工作方式，以及参与时须遵守的三条守则。

## 怎么向代理提需求

- 在 Issue 或 PR 的评论里 `@superagent-hanbo`，并写清你要它做的事。
- 请求必须来自允许列表（allowlist）中的账号；不在允许列表里的账号无法触发代理工作。

## 代理的工作方式

- 每个 Ticket 使用一个独立的工作目录，以及一个独立分支 `agent/<短名>`。
- 改完后代理会开 PR，等待人工评审和合并。
- 代理不会自动合并，合并始终由人完成。

## 三条守则

三条守则按团队原话引用：

1. **起点收窄（Start narrow）**：“a short allowlist and proactive work only recorded, not a narrower request.”
2. **为更少噪音而调（Tune for less noise）**：“shorten the prompts or pause the agent, never add messages to explain the noise.”
3. **它说的话你负责（Own what it says）**：“every message the agent sends costs colleagues' attention and belongs to the operator.”
