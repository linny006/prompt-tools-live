<!--
SEO: prompt tools live
-->

<div align="center">

# Prompt Tools Live

Live-updating tracker of prompt engineering tools, libraries, and techniques — refreshed every 15 minutes

[![Stars](https://img.shields.io/github/stars/linny006/prompt-tools-live?style=for-the-badge&logo=github)](https://github.com/linny006/prompt-tools-live/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/linny006/prompt-tools-live?style=for-the-badge)](https://github.com/linny006/prompt-tools-live/commits)
[![Items](https://img.shields.io/badge/Tracked_Items-7-brightgreen?style=for-the-badge)](#)
[![Updated](https://img.shields.io/badge/Updates-every_15min-blue?style=for-the-badge)](#)

**⭐ Star this repo to bookmark — fresh data every 15 minutes**

[English](./README.md) · [中文](./README_CN.md) · [日本語](./README_JA.md) · [한국어](./README_KO.md) · [Español](./README_ES.md) · [Português](./README_PT.md)

</div>

---

## 💡 What is this?

Automatically discovers and ranks the newest prompt engineering tools, libraries, and notable prompt repos across GitHub and package registries. Refreshes every 15 minutes via GitHub Actions so the catalog always reflects current model capabilities and community activity rather than a stale snapshot.

This list is **auto-updated every 15 minutes** by a GitHub Actions cron.
Each commit reflects a real change in the upstream data source — new items added,
expired items removed — so you can rely on what you see being current.

---

## 📋 Current Items

> ⏰ Last updated: 2026-10-27 15:00 UTC
>
> Data source: `GitHub Search API`
>
> The table below is rewritten on every cron tick. Star the repo to bookmark.

<!-- TRACKER_TABLE_START -->
| # | Name | ⭐ | Lang | Updated | Description |
|---|------|---|------|---------|-------------|
| 1 | [liuweispace/posterloom-sklls](https://github.com/liuweispace/posterloom-sklls) | 1 | Python | 2026-10-27 | Adaptive photo-to-poster skill: scene analysis, identity-anchor preservation, 30-style routing, restrained typography, p |
| 2 | [SanHsien/agent-skills](https://github.com/SanHsien/agent-skills) | 1 | JavaScript | 2026-10-27 | AI coding agent 工程技能包：25 個 skill、9 個 slash command，涵蓋 spec→plan→build→verify→review→ship｜Production-grade engineering sk |
| 3 | [mdl233/ai-pairing-field-notes](https://github.com/mdl233/ai-pairing-field-notes) | 8 | JavaScript | 2026-10-27 | 跟 AI 结对干活的实战笔记：Windows 中文环境 102 条真实坑（附速查表）· 零基础入门 21 节 · 协作纪律 · 把工作留下来的做法 · AI 做界面与美术 · 在国内网络里搞到模型与工具 |
| 4 | [Open-Less/openless](https://github.com/Open-Less/openless) | 3981 | Rust | 2026-10-27 | Hold a key, speak, release — AI-polished text appears at your cursor in any app. Open-source voice input for macOS & Win |
| 5 | [fomativeh/text-transformation-suite](https://github.com/fomativeh/text-transformation-suite) | 0 | — | 2026-10-27 | A set of prompts to handle common text tasks, focusing on clarity and control. |
| 6 | [Arize-ai/phoenix](https://github.com/Arize-ai/phoenix) | 12027 | Python | 2026-10-27 | AI Observability & Evaluation |
| 7 | [kaderkck/hewn-forge](https://github.com/kaderkck/hewn-forge) | 116 | HTML | 2026-10-27 | HEWN 2.0 2026: AI Output Router for Precision Summaries & Polished Code |
<!-- TRACKER_TABLE_END -->

---

## 🔍 How it works

Every 15 minutes, a GitHub Action runs `tracker.py`. That script:

1. Fetches the latest state from `GitHub Search API`.
2. Diffs against `data/items.json` (the previous snapshot).
3. Rewrites the table above between the `<!-- TRACKER_TABLE_* -->` markers.
4. Commits `feat: +N added, -M removed (timestamp)` if anything changed.

No external services. No paid APIs. Just a public data source and a free GitHub Action.

---

## 🤝 Contributing

See `CONTRIBUTING.md` — usually you don't need to: the tracker keeps itself current.
If you spot a data-source bug or want to suggest a new column for the table, open
an issue.

---

## 🔗 Related live trackers

If you find this useful, you might also like these other auto-updated
trackers from the same maintainer — same mechanism, different upstream:

- [trending-claude-skills](https://github.com/linny006/trending-claude-skills) — What's shipping in Claude Skills this week (`topic:claude-skills`)
- [mcp-servers-live](https://github.com/linny006/mcp-servers-live) — Live index of newest MCP servers (`topic:mcp-server`)
- [cursor-rules-live](https://github.com/linny006/cursor-rules-live) — Newest Cursor rules and .cursorrules patterns (`topic:cursor-rules`)
- [claude-code-plugin-tracker](https://github.com/linny006/claude-code-plugin-tracker) — Claude Code plugins and hook configs (`topic:claude-code`)
- [llm-agents-radar](https://github.com/linny006/llm-agents-radar) — Newest LLM agent frameworks (`topic:llm-agent`)
- [rag-radar](https://github.com/linny006/rag-radar) — Newest RAG implementations and tools (`topic:rag`)
- [llm-eval-tracker](https://github.com/linny006/llm-eval-tracker) — Newest LLM evaluation tools and benchmarks (`topic:llm-eval`)
- [agent-framework-radar](https://github.com/linny006/agent-framework-radar) — Newest agent frameworks shipping on GitHub (`topic:agent-framework`)
- [vector-db-live](https://github.com/linny006/vector-db-live) — Newest vector DB projects and integrations (`topic:vector-database`)
- [llmops-radar](https://github.com/linny006/llmops-radar) — Newest LLMOps tooling (observability, deployment) (`topic:llmops`)
- [agent-eval-harness](https://github.com/linny006/agent-eval-harness) — Live benchmark of AI coding agents (`topic:llm-eval`)
- [skills-tracker](https://github.com/linny006/skills-tracker) — Tracking new GitHub 'skills' repos (`topic:agent-skills`)
- [awesome-agent-skills](https://github.com/linny006/awesome-agent-skills) — Curated auto-updated awesome-list of AI agent skills (`topic:agent-skills`)

---

## 📜 License

MIT — see `LICENSE`.
