# BuddyTerm

Your terminal. Your agents. One beautiful workspace.

BuddyTerm is a native macOS app that combines a GPU-accelerated terminal with a polished code editor. Run Claude Code, Codex, or any TUI agent. Review every diff. Roll back mistakes. All in one window — fast, gorgeous, and effortless.

## Download

Grab the latest `BuddyTerm-*.dmg` from the [Releases page](https://github.com/wangleilei2010/buddyterm-releases/releases).

**Requirements:** macOS 14.0 or later.

## Features

- **GPU-accelerated terminal** — powered by libghostty, 60fps scrolling, proper alt-screen buffer handling, full zsh integration.
- **Native code editor** — Scintilla-based, zero input latency, syntax highlighting.
- **Run any TUI agent** — Claude Code, Codex, or any terminal program you already use.
- **Visual diff review** — every agent change shown as a native diff: gutter markers, inline highlights, per-hunk accept/reject, multi-file sidebar.
- **Checkpoint rollback** — one click back to any checkpoint. No `git reflog` archaeology, no lost work.
- **Remote over SSH** — run your agent on a Linux server and review changes locally in the native editor, as if the code was on your machine. Real-time file watching over SSH.
- **Agent task cards** — live status under each terminal showing the current tool, elapsed time, and approval prompts.

## Why BuddyTerm

AI agents that edit code need review. BuddyTerm brings the terminal, the editor, and the diff review into a single native window — no Electron, no web tech, no plugins, no config files. Open a project, start a terminal, run your agent. That's it.

## Built on

- [libghostty](https://github.com/ghostty-org/ghostty) — terminal rendering engine
- [Scintilla](https://www.scintilla.org/) — editor component

---

This repository hosts BuddyTerm release downloads only. The application source code is proprietary and not open-source.
