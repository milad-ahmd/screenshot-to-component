> [!NOTE]
> **This skill now lives in the main collection: [milad-ahmd/agent-skills](https://github.com/milad-ahmd/agent-skills/tree/main/skills/screenshot-to-component)**. Please ⭐ star it there; that's where updates land first.
> Docs: **https://milad-ahmd.github.io/agent-skills/skills/screenshot-to-component/** · Claude Code: `/plugin install all-skills --marketplace milad-ahmd/agent-skills`

<div align="center">

# 🖼️ screenshot-to-component

**Screenshot or mockup to a component built with your design system. An Agent Skill for Claude Code, Cline, Cursor, Codex and other AI coding agents.**

[![License: MIT](https://img.shields.io/github/license/milad-ahmd/screenshot-to-component)](LICENSE)
[![Stars](https://img.shields.io/github/stars/milad-ahmd/screenshot-to-component?style=social)](https://github.com/milad-ahmd/screenshot-to-component)
![Category](https://img.shields.io/badge/category-Frontend-blue)
![Works with](https://img.shields.io/badge/works%20with-Claude%20Code%20%7C%20Cline%20%7C%20Cursor%20%7C%20Codex-8A2BE2)

[Install](#-install) · [Usage](#-usage) · [How it works](skills/screenshot-to-component/SKILL.md) · [All skills](https://github.com/milad-ahmd/agent-skills)

</div>

> Part of **[agent-skills](https://github.com/milad-ahmd/agent-skills)**, a growing collection of practical skills for AI coding agents.

## 📦 Install

**One command (installs the whole collection):**

```bash
curl -fsSL https://raw.githubusercontent.com/milad-ahmd/agent-skills/main/install.sh | bash -s -- screenshot-to-component
```

**Manually (Claude Code):**

```bash
git clone https://github.com/milad-ahmd/screenshot-to-component /tmp/screenshot-to-component
mkdir -p ~/.claude/skills && cp -r /tmp/screenshot-to-component/skills/screenshot-to-component ~/.claude/skills/
```

**Per project:** copy `skills/screenshot-to-component` into `<project>/.claude/skills/`.
**Any other agent:** paste [`SKILL.md`](skills/screenshot-to-component/SKILL.md) into your rules or system prompt.

## 💬 Usage

Just ask your agent:

```text
Build this screenshot as a React component
Implement this mockup in Flutter
```

The full workflow, rules and output format are in [`SKILL.md`](skills/screenshot-to-component/SKILL.md).

## 🧩 More skills

See the full collection: **[milad-ahmd/agent-skills](https://github.com/milad-ahmd/agent-skills)**.

## 🤝 Contributing

Issues and PRs are welcome, especially real-world before/after examples.

## 📄 License

[MIT](LICENSE) © Milad Ahmadi

<div align="center">

**If this skill saved you time, a ⭐ helps others find it.**

</div>
