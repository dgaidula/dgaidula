### Danniel Gaidula

Creative Technologist · Design Systems Architect · Human-Machine Co-Author

I’ve been building the logic of generative systems since before “generative AI” was a category — a rule-based analog computing game at RISD in 2004, a rules-driven interactive map in 2003, an AI tooling layer for my own practice today. The tools change. The question doesn’t: how do you build a system precise enough to be consistent and flexible enough for a person to make it their own.

**Currently building:**

- [`orchestrator-discipline`](https://github.com/dgaidula/orchestrator-discipline) — multi-agent AI work doesn’t fail loudly, it fails silently: work that should parallelize runs serially, subagent reports get trusted as facts, summaries arrive unreadable. An installable Claude Code skill that writes down the delegation disciplines preventing each — in ~130 tokens of always-on context, because a discipline skill that bloats every session is refuting itself.
- [`zsh-claude-cast`](https://github.com/dgaidula/zsh-claude-cast) — a zsh plugin that generates Claude Code launchers from one casting table — each role mapped to a full model ID and effort level — so which model does what stays a visible, editable projection of your scorecard instead of a drawer of aliases that drift out of date with every model release. Session-only by design: it launches through `--model`/`--effort` and never writes `settings.json`. MIT.
- [`google-workspace-mcp`](https://github.com/dgaidula/google-workspace-mcp) — a minimal MCP stdio server exposing Google Workspace write operations that another popular CLI's own MCP server intentionally leaves out. Single file, zero dependencies, raw JSON-RPC 2.0.
- [`root-to-anywhere`](https://github.com/dgaidula/root-to-anywhere) — Claude's built-in Drive connector can't write directly into subfolders. Rather than work around that by hand every time, I paired a file-naming convention with a scheduled Apps Script that relocates and cleans up automatically.
- [`gemini-vectorize`](https://github.com/dgaidula/gemini-vectorize) — a zero-dependency CLI that chains three different AI models (Gemini, Recraft) and a custom cleanup pass into one idempotent image-to-vector pipeline.
- [`claude-config-tune`](https://github.com/dgaidula/claude-config-tune) — a deterministic, report-only linter for Claude Code permission allow-lists, plus a measured method for trimming CLAUDE.md context cost. MIT, shipped as a Claude Code plugin.
- [`claude-rocketline`](https://github.com/dgaidula/claude-rocketline) — a compact, themeable status line for Claude Code styled like a Powerlevel10k prompt: angled powerline segments, git info, a clock, a context-window meter, and a usage-limit reset countdown, with a responsive shed order so it degrades gracefully as the terminal narrows. Bash + jq, no package.json, MIT.

Also maintain a small suite of prepress/SVG/print-automation tools (`process-images`, `svg-color-rinse`, `svg-knockout`, and others) — production-grade image and print engineering, the same discipline applied to a different medium.

**Elsewhere:**<br>
🌐 [gaidula.com](https://www.gaidula.com) — practice, writing, longer-form work<br>
💼 [LinkedIn](https://gaidu.la/linkedin)<br>
✉️ dan@gaidula.com

25 years as a creative technologist. 30 years as a designer. One throughline.
