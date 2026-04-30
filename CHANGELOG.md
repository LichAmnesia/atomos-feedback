# Changelog

User-facing changes to **atomos**.
Format loosely follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).
Versioning is [SemVer](https://semver.org/) — pre-1.0, expect minor versions
to be the meaningful bumps.

Download: <https://orangebot.ai/atomos>

---

## [0.6.2] — 2026-04-29

### Added
- Anonymous daily heartbeat so I can tell whether new builds reach real
  installs. No notes, no queries — only app version + macOS major version.
  Opt-out in Settings → Privacy.

## [0.6.1] — 2026-04-28

### Fixed
- App could crash on first paint for some users. Resolved.

## [0.5.0] — 2026-04-22

### Added
- **Wide markdown tables** — horizontal scroll, sticky first column,
  drag-to-resize column widths. Wide tables stop breaking the page.
- **Resilient embedding indexer.** A single bad batch no longer aborts a
  full re-index — large vaults get through.
- **Memory-suggest chip in Ask.** When the AI surfaces something worth
  remembering, a one-click chip writes it to a memory note in your vault.
- **Ask chat keymap.** `Enter` inserts a newline; `⌘↵` sends. Long
  multi-line questions finally work.
- **Drag & drop from Finder** into the vault.
- **Image preview tab** for `.png` / `.jpg` / `.gif` / `.webp` files —
  no more parser crashes on binary files.
- **Local-graph mini panel** — see the current note's 1-hop neighborhood
  without opening the full graph view.
- **Command-palette launcher icon** in the left ribbon (`⌘⇧P`).

## [0.4.1]

### Added
- Code-block copy with a confirmation toast.
- Auto-update check on startup, plus an updater chip in Settings.
- Semantic search hits scroll to the matching span in the file, not just
  the file.

## [0.4.0]

### Added
- **Global Rewrite (`⌘⇧Y`)** — AI text rewrite anywhere in the active
  editor, with a floating HUD that shows the model running in-place.

### Note
- 0.3.x users will need a one-time manual download to upgrade. OTA
  updates work normally from 0.4.0 onward.

## [0.3.0]

### Added
- Persistent Ask chat history.
- Mermaid diagrams in markdown.

## [0.2.1]

### Fixed
- Subprocess PATH when launched from Finder — Codex / Claude CLI
  integration works again.

## [0.2.0]

### Added
- **Agent Pane** (Claude Code / Codex CLI) folded into Ask.
- **Skills** — 17 bundled persona / workflow chat presets.
- Obsidian-style ribbon on the left rail.
- Markdown rendering + clickable wiki-links inside Ask responses.

## [0.1.2]

### Fixed
- Empty-folder bug — *New folder* / *New atom* now appear immediately
  in the sidebar.

## [0.1.1]

### Fixed
- First-launch papercuts.

## [0.1.0] — first public build

- Local-first Personal Research OS for macOS, Apple Silicon.
- Obsidian-shape editor over plain markdown + git.
- Per-vault semantic index with Ask-this-vault chat.
- AI text reformat (`⌘J` / `⌘⌥J`).
- Native Mac window + a local web UI on the same backend.

[0.6.2]: https://github.com/LichAmnesia/atomos-feedback/releases/tag/v0.6.2
[0.6.1]: https://github.com/LichAmnesia/atomos-feedback/releases/tag/v0.6.1
[0.5.0]: https://github.com/LichAmnesia/atomos-feedback/releases/tag/v0.5.0
[0.4.1]: https://github.com/LichAmnesia/atomos-feedback/releases/tag/v0.4.1
[0.4.0]: https://github.com/LichAmnesia/atomos-feedback/releases/tag/v0.4.0
[0.3.0]: https://github.com/LichAmnesia/atomos-feedback/releases/tag/v0.3.0
[0.2.1]: https://github.com/LichAmnesia/atomos-feedback/releases/tag/v0.2.1
[0.2.0]: https://github.com/LichAmnesia/atomos-feedback/releases/tag/v0.2.0
[0.1.2]: https://github.com/LichAmnesia/atomos-feedback/releases/tag/v0.1.2
[0.1.1]: https://github.com/LichAmnesia/atomos-feedback/releases/tag/v0.1.1
[0.1.0]: https://github.com/LichAmnesia/atomos-feedback/releases/tag/v0.1.0
