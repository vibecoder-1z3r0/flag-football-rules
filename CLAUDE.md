# CLAUDE.md

Context for working on this repo. Keep this file up to date whenever the structure, sources, or
open questions change.

## What this repo is

A version-controlled rulebook for **Lancaster NY** flag football, maintained like a software
spec/RFC (stable rule numbers, revision history, changelog) rather than a folder of PDFs. The
owner (tyraziel) supplies source documents (official league PDFs, screenshots, text messages
describing new house rules); Claude's job is to fold each new source into the structured
rulebook, keeping `rules/rulebook.md` as the single current source of truth.

## Layout and precedence

```
rules/
  rulebook.md            Numbered rules: Rule / Officials Notes / Rationale / Case Plays /
                          Revision History, per rule. Appendix A: Open Issues at the bottom.
  officials-manual.md     Crew mechanics and administrative procedure (not playing rules)
  casebook.md             Play/Ruling case examples, cross-referenced from rulebook.md
  penalty-matrix.md       The ONLY place penalty yardage/enforcement is stated
  glossary.md             Term definitions
  changelog.md            Version history — which document introduced/changed which rule

sources/                 Raw transcriptions of original PDFs — provenance only, never edited
                          for content, never treated as authoritative if rules/ disagrees.
  base-rules/             USA Football ADM Flag Rulebook (national baseline)
  league-rules/lancaster-ny/
    2024/                 Superseded — historical reference only
    2026/                 Current season source docs + custom-additions.md for pending
                          house rules not yet folded into rulebook.md
```

**Precedence when rules conflict** (highest wins):
1. Pending custom additions (not yet finalized — stay in `custom-additions.md` +
   Appendix A "Open Issues" in `rulebook.md` until resolved, never silently merged in)
2. Current-season Lancaster documents (`sources/league-rules/lancaster-ny/2026/`)
3. Older Lancaster documents (`sources/league-rules/lancaster-ny/2024/`) — used to fill gaps
   the current season's docs don't address, and to preserve officiating mechanics that were
   never restated but never contradicted either
4. USA Football baseline (`sources/base-rules/`) — fills any remaining gap

## Working conventions

- **`rules/rulebook.md` is the single answer to "what are the rules right now."** Every rule there
  must state accurate Revision History tracing back to its source(s). If you add/change a rule,
  update its Revision History, update `rules/changelog.md`, and update `rules/penalty-matrix.md`
  if it touches a penalty — don't let these drift out of sync.
- **Never invent a rule to resolve an ambiguity or contradiction.** If two sources disagree in a
  way that isn't a clean "newer beats older," or a source is internally inconsistent (e.g., a sign
  error in a penalty table), log it as a new entry in Appendix A ("Open Issues") of
  `rulebook.md` instead of picking an answer. Only remove an Open Issues entry once the user
  has actually told you the resolution.
- `sources/` holds faithful transcriptions of the original documents — don't editorialize or "fix"
  wording there. All reconciliation/interpretation happens in `rules/`.
- When a new source document arrives:
  1. Figure out where it fits — new base rules? new league? an update to an existing
     league-season, superseding the prior one? a pure confirmation/condensed copy adding no
     new information (skip a separate file, note it as a cross-check instead, per the pattern
     used for the NFL FLAG condensed one-pager)? Ask the user if the relationship isn't clear
     rather than guessing (e.g., "is this the same league updated, or a different league?").
  2. Save a transcription under `sources/<base-rules|league-rules/<league>/<year>>/`.
  3. Update the affected rule(s) in `rules/rulebook.md`, with a new Revision History line citing
     the new source and what it changed/overrode.
  4. Add an entry to `rules/changelog.md` for the new version.
  5. Update `rules/penalty-matrix.md` and/or `rules/glossary.md` if the new source touches
     penalties or introduces new terminology.
  6. If the new source contradicts something without a clean precedence resolution, add it to
     Appendix A of `rulebook.md` instead of guessing.
- House rules the user is still workshopping (not yet reflected in an official league document)
  live in `custom-additions.md`, get a stub in the relevant rule (marked clearly as "pending, not
  yet in force"), and get an Open Issues entry — never get merged into the rule as if final.

## Open questions (as of 2026-07-08)

See `rules/rulebook.md` Appendix A for full detail. Current open items:
- **OI-1** — 4th-down decision clock (~5 sec): concurrent with play clock? default on timeout?
  which divisions?
- **OI-3** — "Failed snap" (2024) vs. "botched exchange" (2026): same rule renamed, or two
  distinct rules?
- **OI-5** — 2024 officiating mechanics (puck system, crew roles, rules-debate procedure,
  enforcement philosophy) not restated in 2026 docs; carried forward as still-current pending
  confirmation.
- **OI-6** — Roster min/max size not specified in any 2026 document; baseline (5–10, min 4 in
  an emergency) used as fallback.
- **OI-7** — Whether the 2026 overtime format applies to all games or only playoffs (baseline
  restricted overtime to playoffs; 2026 docs don't restate that restriction).

**Resolved:** OI-2 (illegal-timeout clock runoff — 2026 supersedes 2024 outright, no
reconciliation needed) and OI-4 (offensive Unnecessary Roughness sign — confirmed dash typo,
-10 yards is correct). See `rules/rulebook.md` Appendix A, "Resolved Issues" for the record.

Resolve these with the user, then update `custom-additions.md` / the relevant rule /
`changelog.md`, and remove the resolved item from both `rulebook.md` Appendix A and this list.
