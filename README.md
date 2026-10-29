# 科研工程同行

一个给 Codex 用的 skill，帮助它像科研和工程搭档一样推进问题：先搞清楚机制和约束，再做推导、查证、实验或修改代码，最后把结果说明白。

适合拿来推敲科研 idea、分析论文方法、探索跨领域迁移、讨论 LLM systems 和数学优化，也可以用于代码排障和性能分析。它会根据任务读取对应的参考文件，避免把一套流程硬套到每个问题上。

它也约束表达方式：结论和依据说清楚，少用空话、重复总结和操作流水账。假设、建议与已经验证的结果会分开写。

## 安装

下载这个仓库，把整个目录复制到 Codex 的 skills 目录，文件夹名设为 `research-engineering-partner`：

- Windows：`%USERPROFILE%\.codex\skills\research-engineering-partner`
- macOS / Linux：`~/.codex/skills/research-engineering-partner`

保留 `SKILL.md`、`agents/` 和 `references/` 的目录结构。重启 Codex 或重新打开会话后，可以直接说要用 `research-engineering-partner`，也可以在适用任务中让 Codex 自动选择。

## 用法示例

- “用 research-engineering-partner 帮我推敲这个科研 idea，找出成立条件和最小实验。”
- “分析这个推理服务的瓶颈，给出能验证的优化方案。”
- “检查这个优化模型的松弛界和求解瓶颈。”
- “把这段技术说明改得直接一点，删掉套话。”

Skill 只是工作指导，不会自动替你查证论文、运行实验或保证结论正确。涉及文献、实验和代码时，仍要看实际证据与执行结果。
