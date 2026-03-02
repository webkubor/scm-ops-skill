---
name: scm-ops-skill
description: "SCM (GitHub/GitLab) Optimization Protocol. Optimized for multi-instance repository management and automated release loops."
version: 1.0.0
author: "司南烛 (Si Nan Zhu)"
license: "MIT"
keywords: ["scm", "github-ops", "gitlab-ops", "git-flow", "automation"]
allowed-tools: ["run_command", "list_dir", "grep_search"]
user-invocable: true
---

# 🛠 SCM Ops Skill (SCM 运维专家)

> **定位**: 跨平台代码托管与分发中枢。负责管理 GitHub 与 GitLab (及 Paylinker 私有实例) 的仓库生命周期、发版闭环与 CI/CD 自动化。

## 📖 核心职责 (Core Responsibilities)

### 1. GitHub 自动化闭环
- **全自动发版**: 闭环处理代码推送、版本升级、CHANGELOG 更新及 Tag 发布。
- **凭证注入**: 动态从 `AI_Common` 提取 Token 并执行安全认证。

### 2. GitLab 实例统管
- **多实例切换**: 智能识别官方与 Paylinker 私有实例，自动切换 Token。
- **CI 状态监测**: 通过 `glab` 追踪流水线健康度，及时向“老爹”汇报异常。

## 🧱 详细内核
- GitHub 操作指南：[references/github-ops.md](references/github-ops.md)
- GitLab 操作指南：[references/gitlab-ops.md](references/gitlab-ops.md)
