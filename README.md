# Questy 🔬

> **Open-Source Universal R&D & Intelligence Suite for Google Antigravity, Claude Code, GitHub Copilot, OpenAI Codex & Perplexity**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Platform: Antigravity](https://img.shields.io/badge/Platform-Google%20Antigravity-4285F4)](https://antigravity.google)
[![Platform: Claude](https://img.shields.io/badge/Platform-Anthropic%20Claude-D97706)](https://anthropic.com)
[![Platform: Copilot](https://img.shields.io/badge/Platform-GitHub%20Copilot-black)](https://github.com/features/copilot)
[![Platform: Perplexity](https://img.shields.io/badge/Platform-Perplexity-20B2AA)](https://perplexity.ai)

Questy is a cross-platform, open-source research and development intelligence suite. It packages seven specialized, institutional-grade skills into a single architecture that works seamlessly across all major AI agent platforms.

---

## ⚡ The 7 Universal R&D Commands

| Command | Skill ID | Core Capability |
| :--- | :--- | :--- |
| **`/rnd-research`** | `rnd-research` | **Evidence-Led Deep Research**: Systematic hypothesis testing, real-time web investigation, and impartial factual analysis. |
| **`/rnd-struct`** | `rnd-struct` | **Multi-Dimensional Structuring**: Transforms raw findings into rigorous schemas, architectural matrices, and taxonomies. |
| **`/rnd-source`** | `rnd-source` | **Source Verification & Credibility Audit**: Evaluates primary sources, flags bias, detects provenance, and ranks confidence. |
| **`/rnd-report`** | `rnd-report` | **Executive Decision-Ready Reports**: Generates concise, high-signal briefings, executive summaries, and action roadmaps. |
| **`/rnd-network`** | `rnd-network` | **Entity & Dependency Mapping**: Models complex relationships, market ecosystems, supply chains, and technical dependencies. |
| **`/rnd-framework`** | `rnd-framework` | **Methodology & Rubric Design**: Creates reusable evaluation criteria, benchmarking scorecards, and testing protocols. |
| **`/rnd-guidelines`** | `rnd-guidelines` | **Analytical Rigor & Truth Standards**: Enforces objectivity, zero-bias validation, and epistemic honesty across tasks. |

---

## 🛠️ Multi-Platform Setup Guide

### 1. 🌐 Google Antigravity (Plugin & Workspace Skills)
Questy is natively configured both as an **Antigravity Workspace Skill set** and an **Antigravity Plugin**:
1. Clone the repo:
   ```bash
   git clone https://github.com/parthongit89/Questy_.git
   ```
2. Open the directory in Google Antigravity.
3. Type **`/`** in the chat prompt — all 7 commands (`/rnd-*`) are instantly available via auto-complete!
4. *(Optional Plugin Discovery)*: Plugin manifest is provided at `.agents/plugins/questy/plugin.json`.

---

### 2. 🤖 Anthropic Claude & Claude Code
- **Claude Code CLI**: Custom slash commands are pre-configured in `.claude/commands/`. Run commands like `/rnd-research` or `/rnd-report` directly inside Claude Code.
- **Claude.ai Projects**: Includes root `CLAUDE.md` automatically recognized by Claude Project knowledge bases.

---

### 3. 🐙 GitHub Copilot
- **VS Code & JetBrains**: Configured via `.github/copilot-instructions.md`.
- Copilot chat automatically adopts Questy's research standards, citation hierarchy, and `/rnd-*` commands when opened in your editor.

---

### 4. ⚡ Cursor & OpenAI Codex
- **Cursor IDE**: Pre-configured with `.cursorrules` in the repository root.
- All OpenAI GPT-4o / Codex / Claude models in Cursor automatically follow the Questy R&D workflow.

---

### 5. 🔍 Perplexity AI (Spaces / Collections)
- Open `perplexity/SYSTEM_PROMPT.md`.
- Copy the system prompt into your **Perplexity Space / Collection** system instructions.
- Use prefixes like `[RESEARCH]`, `[STRUCT]`, `[REPORT]` or slash commands directly in Perplexity search queries.

---

## 📁 Repository Architecture

```text
Questy_/
├── .agents/
│   ├── plugins/questy/          # Antigravity Plugin bundle
│   │   ├── plugin.json          # Plugin manifest
│   │   └── rules/AGENTS.md      # Plugin active rules
│   └── skills/                  # Antigravity Workspace Skills
│       ├── rnd-framework/
│       ├── rnd-guidelines/
│       ├── rnd-network/
│       ├── rnd-report/
│       ├── rnd-research/
│       ├── rnd-source/
│       └── rnd-struct/
├── .claude/
│   └── commands/                # Claude Code CLI slash commands
├── .github/
│   └── copilot-instructions.md  # GitHub Copilot custom instructions
├── perplexity/
│   └── SYSTEM_PROMPT.md         # Perplexity Space/Collection system prompt
├── .cursorrules                 # Cursor & OpenAI Codex IDE rules
├── CLAUDE.md                    # Anthropic Claude instructions
├── VENTURE_BLUEPRINT.md         # Institutional deep-tech system architecture
├── LICENSE                      # MIT Open-Source License
└── README.md                    # Universal documentation
```

---

## 📄 License
Released under the [MIT License](LICENSE). Open-source for personal, academic, and enterprise research teams.
