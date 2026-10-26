<!--
SEO: prompt tools live
-->

<div align="center">

# Prompt Tools Live

Live-updating tracker of prompt engineering tools, libraries, and techniques — refreshed every 15 minutes

[![Stars](https://img.shields.io/github/stars/linny006/prompt-tools-live?style=for-the-badge&logo=github)](https://github.com/linny006/prompt-tools-live/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/linny006/prompt-tools-live?style=for-the-badge)](https://github.com/linny006/prompt-tools-live/commits)
[![Items](https://img.shields.io/badge/Tracked_Items-11-brightgreen?style=for-the-badge)](#)
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

> ⏰ Last updated: 2026-10-26 10:00 UTC
>
> Data source: `GitHub Search API`
>
> The table below is rewritten on every cron tick. Star the repo to bookmark.

<!-- TRACKER_TABLE_START -->
| # | Name | ⭐ | Lang | Updated | Description |
|---|------|---|------|---------|-------------|
| 1 | [voytas75/PromptManager](https://github.com/voytas75/PromptManager) | 4 | Python | 2026-10-26 | PromptManager is a desktop application for cataloguing, searching, and executing AI prompts, and much more. |
| 2 | [tinyhumansai/tinyjuice](https://github.com/tinyhumansai/tinyjuice) | 21 | Rust | 2026-10-26 | A juicy token compression algorithm. Compress upto 95% of tokens without any loss. Free & Opensource |
| 3 | [gw1450048532-arch/dsh-prompt-enhancer](https://github.com/gw1450048532-arch/dsh-prompt-enhancer) | 0 | JavaScript | 2026-10-26 | A "✨ Enhance prompt" button for the DeepSeek Harness chat composer: rewrite the current draft with the model and write i |
| 4 | [mlflow/mlflow](https://github.com/mlflow/mlflow) | 28537 | Python | 2026-10-26 | The open source AI engineering platform for agents, LLMs, and ML models. MLflow enables teams of all sizes to debug, eva |
| 5 | [Global-AI-Group-Inc/content-generation-skills](https://github.com/Global-AI-Group-Inc/content-generation-skills) | 6 | JavaScript | 2026-10-26 | Mira AI content generation skills: genre playbooks and prompting knowledge for AI agents that generate video and images  |
| 6 | [digline/digline](https://github.com/digline/digline) | 9 | Python | 2026-10-26 | Regression testing for LLM applications in CI. Sample your reference and a score drop is read against how much that scor |
| 7 | [subhacademic-cmd/prompt-craft-ecommerce-visuals](https://github.com/subhacademic-cmd/prompt-craft-ecommerce-visuals) | 2 | HTML | 2026-10-26 | AI E-Commerce Visuals 2026: Ultimate GPT-Image Prompts Library ✨ |
| 8 | [Atheerameer/agentic-cli-blueprint-library](https://github.com/Atheerameer/agentic-cli-blueprint-library) | 0 | HTML | 2026-10-26 | Unlock 1000+ Universal Agentic AI Skills 2026 - Claude, Gemini, Cursor Scripts |
| 9 | [belajarcarabelajar/vivera](https://github.com/belajarcarabelajar/vivera) | 0 | JavaScript | 2026-10-26 | Production-grade AI coding-agent skill pipeline: brainstorm, deep research, plan, human approval gate, strict TDD, subag |
| 10 | [DaveHomeAssist/prompt-lab](https://github.com/DaveHomeAssist/prompt-lab) | 3 | JavaScript | 2026-10-26 | Prompt engineering workbench for web, browser, desktop, iPhone, and iPad |
| 11 | [comet-ml/opik](https://github.com/comet-ml/opik) | 22930 | Python | 2026-10-26 | Debug, evaluate, and monitor your LLM applications, RAG systems, and agentic workflows with comprehensive tracing, autom |
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
