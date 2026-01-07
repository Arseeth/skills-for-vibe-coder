# 🛠️ Skills for Vibe Coder

<p align="center">
  <em>为 Vibe Coder 量身定制的 Claude Skill 集合</em>
</p>

<p align="center">
  <a href="./README.md">English</a>
</p>

---

## ✨ 概述

本仓库包含一系列精心设计的 Claude Skills，旨在提升你的编码工作流。每个 Skill 都针对基于代理的交互进行了优化，并遵循 Skill 编写的最佳实践。

## 📦 安装

将所有 Skills 复制到你的 Claude skills 目录：

```bash
cp -r skills/* ~/.claude/skills/
```

## 🎯 可用 Skills

| Skill | 描述 |
|-------|------|
| 🔍 [ast-grep-rule-crafter](skills/ast-grep-rule-crafter) | 基于 AST 的结构化搜索与重写规则 |
| 📝 [clean-code-reviewer](skills/clean-code-reviewer) | 代码质量审查与最佳实践 |
| 📄 [doc-consistency-reviewer](skills/doc-consistency-reviewer) | 文档一致性检查器 |

## 📖 Skill 详情

### 🔍 ast-grep-rule-crafter

使用 YAML 编写 `ast-grep` 规则的综合参考。涵盖原子模式、组合规则、关系运算符和项目级配置。

### 📝 clean-code-reviewer

提供系统性的代码质量审查指导，专注于可读性、可维护性以及对整洁代码原则的遵守。

### 📄 doc-consistency-reviewer

通过检查命名规范、格式标准和项目内容的一致性，确保文档的统一性。

## 🤝 贡献

欢迎提交 Issue 和功能建议！

## 📜 许可证

MIT
