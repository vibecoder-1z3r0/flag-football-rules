# CLAUDE.md

Context for working on this repo. Keep this file up to date whenever the structure, sources, or
open questions change.

## What this repo is

A personal flag football rule set, built by layering league-specific modifications on top of a
national base rulebook. The owner (tyraziel) is compiling years of downloaded/scanned league
documents into one coherent, current ruleset for **Lancaster NY** flag football.

## Layout and precedence

```
base-rules/
  usa-football-flag-rulebook.md          National baseline (USA Football ADM Flag Rulebook)

league-rules/lancaster-ny/
  2024/                                   Prior season — historical reference only, not authoritative
    lancaster-ny-flag-rules-2024.md
  2026/                                   Current season
    2026-general-rules-and-guidelines.md  Full current league rules (primary source for 2026)
    2026-coaches-cheat-sheet.md           Condensed version of the same rules
    2026-penalty-buddy.md                 Penalty-only quick-reference card
    custom-additions.md                   New house rules not yet in any official league doc

current-rules.md                          MERGED view — the actual answer to "what are the rules"
README.md                                 Repo orientation for humans
```

**Precedence when rules conflict** (highest wins):
1. `league-rules/lancaster-ny/2026/custom-additions.md` (pending house rules)
2. `league-rules/lancaster-ny/2026/2026-general-rules-and-guidelines.md` (current league rules)
3. `base-rules/usa-football-flag-rulebook.md` (national baseline)

The 2024 Lancaster doc is superseded by the 2026 doc — same league, updated rules — and is
kept only for historical comparison, not merged into `current-rules.md`.

## Working conventions

- **`current-rules.md` is the single source of truth for "what do the rules say right now."** Every
  time a source document changes or a new modification/house rule is added, update
  `current-rules.md` to reflect it — don't let it drift out of sync with the individual source files.
- Source documents (base rules, league docs) are transcriptions of PDFs/images the user
  uploads. Transcribe faithfully — don't editorialize or "fix" the source wording. Reconciliation
  and interpretation happens only in `current-rules.md`.
- When a new source document arrives:
  1. Figure out where it fits (new base rules? new league? update to an existing league-season?
     a standalone confirmation/condensed copy of something already captured?). Ask the user if
     the relationship between a new doc and existing docs isn't clear (e.g., "is this the same
     league updated, or a different league?") rather than guessing.
  2. Save a transcription under the right `league-rules/<league>/<year>/` (or `base-rules/`) path.
  3. Re-derive `current-rules.md` from the (possibly new) precedence order.
  4. Update this file's "Open questions" section and the README if the structure changed.
- Condensed/cheat-sheet documents that are pure subsets of a fuller document (no new
  information) don't need their own file if they'd just duplicate content — note them as a
  cross-check instead (see README "Notes on sources"). Only give them a file if they add
  detail not present elsewhere (as `2026-coaches-cheat-sheet.md` and `2026-penalty-buddy.md`
  do).
- House rules the user is still workshopping (not yet reflected in an official league document)
  go in `custom-additions.md` with explicit open questions, and get flagged in the "Open Items"
  section at the bottom of `current-rules.md` — don't silently pick a default for an undecided
  rule.

## Open questions (as of 2026-07-08)

From `league-rules/lancaster-ny/2026/custom-additions.md` — 4th-down decision clock (~5
seconds for a coach to declare go-for-it vs. punt on 4th down, FR/JV divisions):
1. Does the 5-second decision clock run concurrently with, or before, the 30-second play clock?
2. What happens if the coach doesn't declare in time — default to going for it, or a delay-of-game
   penalty?
3. Does this apply to all divisions, or only FR/JV (Peewee has no go/punt decision at all today)?

Resolve these with the user, then update `custom-additions.md`, `current-rules.md`, and remove
them from this list.
