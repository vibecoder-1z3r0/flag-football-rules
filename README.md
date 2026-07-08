# flag-football-rules

A version-controlled rulebook for Lancaster NY Flag Football — built like a software spec/RFC
rather than a stack of league handouts, with a stable rule-numbering scheme, separated
officiating guidance, case plays, and a single penalty matrix.

## Start here

- **[`rules/rulebook.md`](rules/rulebook.md)** — the numbered, authoritative rule set. Read this
  first. Every rule states its current text, officiating notes, rationale where useful, and revision
  history back to its source document. Unresolved contradictions/gaps are logged in its
  **Appendix A: Open Issues** rather than silently decided.

## Layout

```
rules/
  rulebook.md            The rulebook — numbered rules (Rule / Officials Notes / Rationale /
                          Case Plays / Revision History), plus Appendix A: Open Issues
  officials-manual.md     Officiating mechanics: crew positioning, puck system, penalty
                          enforcement procedure, rules-debate process
  casebook.md              Illustrative case plays (Play / Ruling), cross-referenced from rulebook.md
  penalty-matrix.md        Single canonical penalty enforcement table
  glossary.md              Term definitions used throughout
  changelog.md             Version history: which source document introduced/changed each rule

sources/                  Raw transcriptions of the original documents — provenance only,
                          not authoritative. If rules/ and sources/ ever disagree, rules/ wins.
  base-rules/
    usa-football-flag-rulebook.md         USA Football ADM Flag Rulebook (national baseline)
  league-rules/lancaster-ny/
    2024/                                  2024 league rules (superseded, kept for history)
    2026/                                  2026 league rules (general rules, cheat sheet,
                                            penalty card, plus custom-additions.md for
                                            pending house rules)
```

## How rules are resolved

Precedence (highest wins): pending custom additions → current-season Lancaster documents →
older Lancaster documents → USA Football baseline. Where the league is silent, the baseline
fills the gap. See `rules/rulebook.md`'s intro and `rules/changelog.md` for the full reasoning
behind every override.

## Open questions

Anything ambiguous, contradictory across source documents, or missing an edge case is logged
in `rules/rulebook.md` Appendix A rather than guessed at. Check there before assuming a rule is
settled.
