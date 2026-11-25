---
slug: zh-cn/real-world-development/cli
title: "GitHub Copilot CLI"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

**[GitHub Copilot CLI](https://docs.github.com/copilot/concepts/agents/about-copilot-cli)** 将 GitHub Copilot 作为代理式编码助手带入终端。它可以探索代码库、生成代码、运行命令，并连接外部工具——全部通过命令行完成，无需切换到图形化编辑器即可保持工作流畅。

在这些练习中，将先安装并验证 Copilot CLI，然后通过自定义说明为它提供项目上下文，再使用计划模式有目的地生成一个功能。接着连接 Playwright MCP 服务器，在真实浏览器中测试该功能；然后通过可复用的智能体技能和自定义智能体扩展 Copilot。最后，将探索用于管理上下文、模型和共享的斜杠命令，并回顾已完成的内容。还可以学习[使用 GitHub Copilot CLI 和 Foundry 的可选系列课程][foundry]，通过三个模块准备模型、构建并部署托管智能体，以及将其集成到网站中。

## 练习

| 练习 | 主题 | 说明 |
|----------|-------|-------------|
| [0. 先决条件][ex0] | 设置 | 创建存储库和 codespace |
| [1. 安装 Copilot CLI][ex1] | 安装 | 安装并验证 Copilot CLI |
| [2. 添加星级评分：快速完成一项改进][ex2] | 首次更改 | 显示现有评分和未评分时的备用文本，然后合并首个拉取请求 |
| [3. 代理模式：Plan 和 Autopilot][ex3] | 代理模式 | 根据议题规划功能，使用 Autopilot 构建，再通过 Interactive 模式审查 |
| [4. 使用自定义说明引导 Copilot][ex4] | 上下文 | 查看并更新说明，然后将其应用于筛选功能 |
| [5. 自定义并使用 quality-checks 技能][ex5] | 可重复执行的检查 | 查看现有技能、更改报告格式并运行技能 |
| [6. 使用 Playwright MCP 验证功能][ex6] | 浏览器观察 | 在 CLI 中配置 MCP 并检查筛选行为 |
| [7. 创建并使用 QA 代理][ex7] | 要求与覆盖率 | 创建并选择专用配置文件，然后收集最终验证证据 |
| [8. 创建并合并功能拉取请求][ex8] | 审查与合并 | 审查完整更改、创建拉取请求并使用 Agent Merge |
| [9. GitHub Copilot CLI 斜杠命令][ex9] | CLI 功能 | 探索上下文、模型、共享，以及可选的云代理委派 |
| [10. 总结和后续步骤][ex10] | 总结 | 回顾工作流、可重复使用的自定义项和更多资源 |
| [可选：集成 Foundry][foundry] | 托管智能体 | 准备模型、构建并部署基于目录的 Backer Concierge，并将其连接到网站 |

## 先决条件

参加本工作坊前，请确保已具备以下条件：

- [ ] 拥有 GitHub 账户，并已启用 **Copilot Student、Pro、Pro+、Business 或 Enterprise** 计划
- [ ] 对终端/命令行操作有基本了解
- [ ] 已安装并配置 Git

> [!TIP]
> 没有付费计划？已验证学生可通过 [GitHub Education][callout-student-plan-education] 免费使用 GitHub Copilot。**Copilot Student** 计划包含本工作坊所用的智能体、MCP、代码审查和 Copilot CLI 功能，因此可以完整完成所有路径。

[callout-student-plan-education]: https://github.com/education/students

> [!NOTE]
> 如果使用的是 Copilot Business 或 Copilot Enterprise，请确认管理员已启用 Copilot CLI。

## 开始

**[从练习 0：先决条件开始 →][ex0]**

[ex0]: 0-prerequisites/
[ex1]: 1-install-copilot-cli/
[ex2]: 2-add-star-rating/
[ex3]: 3-agent-modes/
[ex4]: 4-custom-instructions/
[ex5]: 5-agent-skills/
[ex6]: 6-mcp-playwright/
[ex7]: 7-qa-agent/
[ex8]: 8-create-pull-request/
[foundry]: 8-foundry-agent/
[ex9]: 9-cli-power-tools/
[ex10]: 10-review/
