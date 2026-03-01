# 🎮 ai-coding-playground

> **Developed by 소담 AI 스튜디오**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Claude Code](https://img.shields.io/badge/Claude-SubAgent-blue)](https://claude.ai)
[![Language: Korean](https://img.shields.io/badge/Language-Korean-green)](./README.ko.md)

A Claude Code SubAgent that guides complete non-developers through AI coding tools — covering MCP servers, Skills, SubAgents, Extensions, Hooks, and Workflow automation across Claude Code, Cursor, Windsurf, VS Code + Copilot, and Google Antigravity.

[한국어 README →](./README.ko.md)

---

## ✨ What It Does

`ai-coding-playground` is a SubAgent that acts like a friendly tutor — explaining every concept through everyday analogies before touching a single config file. It targets users who have never written a line of code and want to harness modern AI coding tools from day one.

**Core capabilities:**

- **Tool selection guide** — compares Claude Code, Cursor, Windsurf, VS Code + Copilot, and Google Antigravity side-by-side
- **MCP server setup** — installs and configures MCP servers with copy-paste-ready JSON for every supported tool
- **Project rule files** — generates `CLAUDE.md`, `.cursorrules`, `.windsurfrules`, `copilot-instructions.md`, and `AGENTS.md`
- **Skills & SubAgent creation** — scaffolds `.claude/skills/` and `.claude/agents/` with working templates
- **Hooks & Workflow automation** — sets up `PreToolUse` / `PostToolUse` hooks and multi-agent pipelines
- **Cross-tool migration** — converts config files between any two supported tools instantly
- **One-click project setup** — generates the full config stack for a chosen project type in one command
- **Cost optimization** — recommends the right model (Opus / Sonnet / Haiku) per task type
- **Auto error diagnosis** — detects and fixes common MCP and config errors automatically

---

## 📦 Installation

Copy `ai-coding-playground.md` to your Claude Code agents folder:

```bash
# Mac / Linux
cp ai-coding-playground.md ~/.claude/agents/

# Windows
copy ai-coding-playground.md %USERPROFILE%\.claude\agents\
```

No `CLAUDE.md` setup required — the agent activates automatically via built-in self-routing keywords.

---

## 🚀 Usage

Once installed, trigger the agent naturally in Claude Code:

```
"What is MCP?"
"Set up MCP in Cursor"
"Create a SubAgent for code review"
"Make a project setup for Next.js"
"Migrate my .cursorrules to Claude Code"
"Which AI coding tool should I use?"
"My MCP server won't start"
"How do I reduce AI costs?"
```

---

## 🗺️ Learning Roadmap

The agent guides users through six progressive levels:

| Level | Topic | Goal |
|-------|-------|------|
| 1 | Choose & install an AI coding tool | First AI conversation |
| 2 | Write project rule files | "Always respond in Korean" |
| 3 | Install Extensions / Plugins | 3+ extensions working |
| 4 | Connect MCP servers | 3+ MCP servers connected |
| 5 | Create Skills & SubAgents | 1 custom Skill + 1 SubAgent |
| 6 | Build Workflows & Orchestration | Fully automated code → commit pipeline |

---

## 🛠️ Supported Tools & Concepts

| Category | Supported |
|----------|-----------|
| AI Coding Tools | Claude Code, Cursor, Windsurf, VS Code + Copilot, Google Antigravity |
| Config Files | CLAUDE.md, .cursorrules, .windsurfrules, copilot-instructions.md, AGENTS.md |
| MCP Servers | filesystem, github, git, sqlite, postgres, fetch, context7, memory, sequential-thinking |
| Claude Code Features | Skills, SubAgents, Hooks (PreToolUse / PostToolUse), settings.json |
| Concepts Explained | MCP, Token, Context Window, API Key, Prompt Engineering, Orchestration |

---

## 📋 Key Design Principles

1. **Zero assumptions** — every step explained as if the user has never opened a terminal
2. **Analogy-first** — every concept introduced through a familiar everyday comparison
3. **Korean 100%** — all output in Korean; technical terms shown with Korean translation
4. **Copy-paste ready** — every config file works as-is, no manual editing required
5. **Progressive learning** — one concept at a time, never skipping steps

---

## 📁 Repository Structure

```
ai-coding-playground/
└── ai-coding-playground.md   # Claude Code SubAgent definition
```

---

## 📄 License

MIT License — Copyright (c) 2026 소담 AI 스튜디오

See [LICENSE](./LICENSE) for details.
