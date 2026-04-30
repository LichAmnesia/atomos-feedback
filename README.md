# atomos · feedback

Public feedback board for **[atomos](https://orangebot.ai/atomos)** — a local-first
personal research OS for macOS.

This repo holds **no source code** — only issues, discussions, and the public
changelog. The app itself ships as a signed `.dmg` from
[orangebot.ai/atomos](https://orangebot.ai/atomos).

---

## Where things go

| You want to… | Use |
|---|---|
| Report a bug | [**New issue → Bug report**](https://github.com/LichAmnesia/atomos-feedback/issues/new?template=bug_report.yml) |
| Request a feature | [**New issue → Feature request**](https://github.com/LichAmnesia/atomos-feedback/issues/new?template=feature_request.yml) |
| Ask a question / share a workflow | [**Discussions → Q&A**](https://github.com/LichAmnesia/atomos-feedback/discussions/categories/q-a) |
| Show off your vault setup | [**Discussions → Show & tell**](https://github.com/LichAmnesia/atomos-feedback/discussions/categories/show-and-tell) |
| Vote on what to build next | [**👍 react** on issues](https://github.com/LichAmnesia/atomos-feedback/issues?q=is%3Aissue+is%3Aopen+sort%3Areactions-%2B1-desc) |
| See what shipped | [**CHANGELOG.md**](./CHANGELOG.md) · [**Releases**](https://github.com/LichAmnesia/atomos-feedback/releases) |

---

## Boards

Issues are labeled to mirror a roadmap board:

- `status: under-review` — triaged, deciding whether to build
- `status: planned` — committed, not started
- `status: in-progress` — actively being built
- `status: shipped` — released; check the linked version
- `status: declined` — out of scope (with a reason)

Sort the issue list by [👍 reactions](https://github.com/LichAmnesia/atomos-feedback/issues?q=is%3Aissue+is%3Aopen+sort%3Areactions-%2B1-desc)
to see what the community wants most.

---

## Filing a good bug report

The bug template asks for it, but to save a round-trip:

1. **atomos version** — Settings → About, or the title bar
2. **macOS version** — `About This Mac`
3. **What you did, what happened, what you expected**
4. **Console logs** if it's a crash — `Console.app` → search `atomos`
5. **A vault snippet** that triggers it, if it's parser-shaped

Don't attach your full vault. A 3-file repro is plenty.

---

## What atomos is

Short version: an Obsidian-shape editor over plain markdown + git, with
semantic search, Ask-this-vault chat, and AI text reformat — all local-first,
BYOK. Long version: [orangebot.ai/atomos](https://orangebot.ai/atomos).

Source code is private for now. This may change; either way, the **vault format
is just markdown + git**, so nothing locks you in.

---

## Maintainer

[Shen Huang](https://x.com/shenhuang) · solo author. Triage cadence is
best-effort — expect a response within a few days, not minutes. Security issues:
email `me@alwa.info` instead of opening a public issue.
