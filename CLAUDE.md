# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

BusyBeaver is a **documentation / public-facing repository** for an agent-native knowledge base of public-domain classic books. There is **no code, build system, tests, or dependencies** here — the repository currently holds only prose (README variants), the license, and the logo asset. The actual Meme corpus described in the README is not (yet) checked in; treat this repo as the project's public front page.

Because there is nothing to build or test, most work here is **editing Markdown**. Do not invent build/lint/test commands.

## Repository layout

- `README.md` — the **official English** version and the source of truth for all content.
- `README.zh.md`, `README.es.md`, `README.fr.md`, `README.de.md`, `README.ja.md` — translations of the English README.
- `LICENSE` — PolyForm Noncommercial License 1.0.0.
- `assets/logo.png` — project logo, embedded at the top of every README (`width="220"`, path `./assets/logo.png`).
- `private/` — git-ignored local-only working directory; never commit its contents.

## Working with the multilingual READMEs

The six READMEs are parallel translations that must stay in sync:

- **English is canonical.** When a content change originates in another language, apply it to `README.md` first, then propagate to the other five.
- **Any substantive edit to one README should be mirrored across all six.** The language switcher (`<sub>🌐 English (official) · 简体中文 · …</sub>`) and shared structure (centered header block, logo, section order) must match across variants.
- Keep the project's coined terminology **consistent and untranslated where the README treats it as a proper term**: **Meme** (the atomic knowledge unit), **PN / Purple Number** (provenance address), **provenance control**, **BusyBeaver**.

## Domain concepts (so edits stay accurate)

- **Meme** — the atomic unit: a natural-language *assertion* + *metadata* + *provenance (PN)*. Memes are meant to be distributable and composable.
- **PN (Purple Number)** — an address anchoring each assertion to its source passage; the mechanism for controlling LLM hallucination via traceability. Framed as Doug Engelbart's "every piece of knowledge should have an address."
- The framing metaphors (knowledge "packet-switching", "grass vs. meat", Busy Beaver as fastest-growing function) are load-bearing brand language — preserve their meaning if you touch those sections.
- Corpus is **public-domain books only**; copyrighted material is handled by a separate forthcoming service. Keep this distinction intact in any edit about scope.

## Conventions

- Contact address in the README is **minnie.sew.da@gmail.com** (Minnie Katz). Do not change or invent contact details.
- **Do not commit automatically.** Commit only when the user explicitly asks; stage and confirm first.
- When replacing the logo, keep it at `assets/logo.png` (so no README edits are needed) and compress large source images (the repo target is a 512×512 PNG).
