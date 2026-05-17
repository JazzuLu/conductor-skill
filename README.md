# Conductor: Meta-Skill Orchestrator

`Conductor` 是一个项目无关（Project-Agnostic）的工程调度器。它作为 **翻译层 (Translation Layer)**，有机串联了 `Superpowers` (纪律)、`OpenSpec` (规格) 和 `GStack` (专家) 三大技能系统。

## 🌟 核心特性

- **意图折射 (Intent Refraction)**：自动判定任务能量级（高/中/低风险），并匹配最佳工作流。
- **接力棒协议 (Baton Protocol)**：在不同 Skill 之间自动翻译上下文，防止语义丢失。
- **回声校验 (Echo Verification)**：强制要求 Skill 反述指令，消除 AI 理解偏差。
- **CSO 安全加固**：自动识别并脱敏 API Key 等敏感信息，确保状态锁安全。
- **跨项目适配**：使用系统级存储，不污染业务仓库。

## 🛠 安装方式

将 `SKILL.md` 复制到你的全局 AI 技能目录：
```bash
cp SKILL.md ~/.agents/skills/conductor/SKILL.md
```

## 🚀 使用指南

在任何项目中，直接通过 `/conductor` 唤醒：

- **严重 Bug 修复**: `/conductor 线上导出功能崩溃，请接管。` (进入 FORTRESS 模式)
- **新功能开发**: `/conductor 为项目增加 OAuth2 支持。` (进入 FOUNDATION 模式)
- **UI/UX 优化**: `/conductor 仪表盘样式太老旧了，优化一下。` (进入 PULSE 模式)
- **技术调研**: `/conductor 调研一下 Qdrant 的集成方案。` (进入 SPIKE 模式)

## 📋 接力棒示例 (The Baton)

当 Conductor 完成一次调度，它会生成如下接力棒：

```markdown
### [CONDUCTOR BATON]
**From**: gstack-plan-eng-review
**To**: openspec-apply
**Context**: 发现核心逻辑缺少并发锁。
**Side Effects**: 增加锁可能导致高并发下的性能下降。
**Action Required**: 请在 Task 1 中增加分布式锁实现。
```

## 🛡 安全声明
本工具仅作为辅助调度，所有代码变更必须经过 `superpowers/verification-before-completion` 的最终验证。
