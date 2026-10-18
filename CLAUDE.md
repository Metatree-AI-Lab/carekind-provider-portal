# CLAUDE.md — 机构管理端（Provider Portal）（carekind-provider-portal）

> 层级：代码仓库 · 本 repo 是 meta repo [`Metatree-AI-Lab/carekind`](https://github.com/Metatree-AI-Lab/carekind) 的 submodule，路径 `06-app-development/provider-portal/`。
> 本文件给 AI 看；给人看的说明在同目录的 `README.md`。

## 这里是什么
养老院 business owner、Facility Manager、DON、Care Manager、Provider admin 用的管理端：多院多地点、员工和住户管理、流程管理、看板。同一份代码也部署为 Demo 环境（虚构数据）。

技术栈：React + TypeScript。

## 本 repo 的规则
- **所有文档都在 meta repo**：PRD、ADR、架构、设计规范、文书模板、调研、changelog 都不放在这里。这里只放代码、测试、CI 配置。
- 写代码前先读 meta repo 的 `AGENTS.md`、`rules/02-code-rules.md`（Tab 缩进 4、单文件 ≤ 1000 行、禁用 any、只用合成测试数据）和 `docs/PRD.md` §9 护栏。
- 改完代码：先在本 repo 提交并推送，再回到 meta repo 提交 submodule 指针。
- 共用工具（`.editorconfig`、`scripts/check-*.sh`）以 meta repo 为准，由 meta repo 的 `scripts/sync-app-tooling.sh` 同步。
- 不在日志里记录音频、转写文本、住户姓名或任何健康信息。

## 相关
- meta repo `docs/prds/2026-10-18-provider-portal-facility-admin.md`
- meta repo `06-app-development/engineering/adr/0005-polyrepo-and-mvp-tech-stack.md`（repo 结构与技术栈）
