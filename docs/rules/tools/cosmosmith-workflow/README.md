# Cosmosmith 多 Agent 工作流治理 .cursorrules 提示文件

## 你可以构建什么

- **多 Agent 软件项目**：让 Cursor、Claude Code、Codex、Copilot、OpenCode 和 Trae 共享同一套项目规则
- **规格驱动工作流**：从想法、提案、设计、任务到账本化验证证据
- **团队协作项目**：用角色、任务状态和检查命令减少 AI 协作中的上下文漂移

## 概要

这个规则文件为使用 Cosmosmith 的项目提供多 Agent 工作流治理规则。它把 `AGENTS.md` 视为项目宪法，把 `.cursor/rules/*.mdc`、`CLAUDE.md`、`.github/copilot-instructions.md` 等文件视为工具适配器，并要求通过 `task.md` 记录任务、验证证据和完成状态。

## 核心特性

- 以 `AGENTS.md` 作为唯一权威规则源
- 使用 `task.md` 管理 claim、review、verify、done 状态
- 明确 Prompt、Context、Harness、Loop 四个工作面
- 支持产品、架构、UI/UX、前端、后端、QA、DevOps、治理评审等角色协作
- 在标记完成前记录测试、构建、浏览器 QA 或人工验证证据

## 技术栈

- Cursor Project Rules
- AGENTS.md
- Claude Code / Codex / Copilot / OpenCode / Trae adapters
- Spec-driven development
- DevOps verification loops

## 可选初始化器

```bash
npx cosmosmith@latest init --all
```

项目地址：https://github.com/devnomad-byte/cosmosmith
