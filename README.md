<!--
SEO: prompt tools live
-->

<div align="center">

# Prompt Tools Live

Live-updating tracker of prompt engineering tools, libraries, and techniques — refreshed every 15 minutes

[![Stars](https://img.shields.io/github/stars/linny006/prompt-tools-live?style=for-the-badge&logo=github)](https://github.com/linny006/prompt-tools-live/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/linny006/prompt-tools-live?style=for-the-badge)](https://github.com/linny006/prompt-tools-live/commits)
[![Items](https://img.shields.io/badge/Tracked_Items-0-brightgreen?style=for-the-badge)](#)
[![Updated](https://img.shields.io/badge/Updates-every_15min-blue?style=for-the-badge)](#)

**⭐ Star this repo to bookmark — fresh data every 15 minutes**

</div>

---

## 💡 What is this?

Automatically discovers and ranks the newest prompt engineering tools, libraries, and notable prompt repos across GitHub and package registries. Refreshes every 15 minutes via GitHub Actions so the catalog always reflects current model capabilities and community activity rather than a stale snapshot.

This list is **auto-updated every 15 minutes** by a GitHub Actions cron.
Each commit reflects a real change in the upstream data source — new items added,
expired items removed — so you can rely on what you see being current.

---

## 📋 Current Items

> ⏰ Last updated: _pending first run_
>
> Data source: `GitHub Search API`
>
> The table below is rewritten on every cron tick. Star the repo to bookmark.

<!-- TRACKER_TABLE_START -->
_The first cron run will populate this section._
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

## 📜 License

MIT — see `LICENSE`.
