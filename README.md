# flag-football-rules

Flag football rule set for Lancaster NY, built from the USA Football base rulebook plus
league-specific modifications.

## Start here

- **[`current-rules.md`](current-rules.md)** — the merged, current-season authoritative ruleset
  (base rules + 2026 Lancaster modifications + pending house rules). Read this first.

## Layout

```
base-rules/
  usa-football-flag-rulebook.md      National baseline rules (USA Football ADM Flag Rulebook)

league-rules/lancaster-ny/
  2024/                              Prior season — historical reference only
  2026/
    2026-general-rules-and-guidelines.md   Current season league rules (full)
    2026-coaches-cheat-sheet.md            Condensed sideline reference
    2026-penalty-buddy.md                  Penalty quick-reference card
    custom-additions.md                    New house rules not yet in an official doc

current-rules.md                    Merged view: base rules overridden by current league rules
```

## Notes on sources

- The NFL FLAG "condensed field rules" one-pager was cross-checked against the full USA
  Football rulebook and found consistent (no material differences) — it isn't kept as a separate
  file since it's a subset of `base-rules/usa-football-flag-rulebook.md`.
- Where Lancaster NY rules conflict with the USA Football base rules, Lancaster rules win.
- Open questions / not-yet-finalized rules live in `league-rules/lancaster-ny/2026/custom-additions.md`
  and are flagged at the bottom of `current-rules.md`.
