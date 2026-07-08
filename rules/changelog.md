# Changelog

Version history of the rulebook. Each version corresponds to a source document (or set of
source documents) folded into `rulebook.md`, `officials-manual.md`, `casebook.md`, and
`penalty-matrix.md`. See `sources/` for the raw transcriptions each version is built from.

Versioning scheme: `v<season>.<revision>` for league documents; `v0` for the USA Football
baseline that everything else layers on top of.

---

## v2026.1 — 2026 Season (current)

**Sources:** `sources/league-rules/lancaster-ny/2026/2026-general-rules-and-guidelines.md`,
`2026-coaches-cheat-sheet.md`, `2026-penalty-buddy.md`

**Summary of changes from v2024.1 / v0:**
- Halftime lengthened from 2 minutes (2024) to 5 minutes.
- Rush-line distances formalized as division-specific: 10 yards (Peewee/Freshman), 7 yards
  (JV/Varsity) — Freshman/Peewee blitzer must self-identify with a raised hand.
- New defensive alignment restriction: Peewee/Freshman/Girls non-blitzing defenders must
  stay 5 yards off the LOS until the snap; only the identified blitzer may line up closer.
- New "botched exchange" (fumbled handoff) rule with division-specific do-over allowances —
  see Open Issue OI-3 regarding overlap with the 2024 "failed snap" rule.
- Overtime format completely replaced: shootout-style, both teams attempt from the same
  distance each round (5 then 10 yards), no coin-toss choice of offense/defense — see Open
  Issue OI-7 on whether this applies to regular-season games or only playoffs.
- PAT/conversion interceptions are now returnable for 2 points (baseline said no return, dead
  immediately).
- Coach-on-field counts formalized by division (Peewee 2, Freshman/Girls FR/JV 1, JV/Varsity 0).
- Jersey colors formalized: Co-ed Home=Red/Away=Black, Girls Home=Red/Away=White.
- Mouthguards made mandatory (baseline only "encouraged" them).
- Punting broadened to any down (2024 restricted the punt election to 4th down for FR/JV).
- Explicit unnecessary-roughness definition and a first-foul-warning /
  second-foul-ejection progressive discipline rule added.
- Illegal-timeout clock runoff changed from 2024's 30-second/under-2:00-remaining trigger to a
  10-second/"disadvantageous" trigger — **flagged as Open Issue OI-2**, wording is unclear.
- Offensive Unnecessary Roughness penalty has a sign discrepancy between source documents
  (+10 vs. -10) — **flagged as Open Issue OI-4**, not resolved.

**Not restated from 2024 (carried forward as still-current, pending confirmation — Open Issue
OI-5):** 2-puck system, primary/line-judge crew role split, midfield rules-debate procedure,
"teach then enforce" progressive enforcement philosophy, timeout-for-rules-clarification
mechanic.

---

## v2024.1 — 2024 Season (superseded)

**Sources:** `sources/league-rules/lancaster-ny/2024/lancaster-ny-flag-rules-2024.md`

**Summary of changes from v0:**
- Downs changed from the baseline's 3-down system to a 4-down system (carried forward
  unchanged into 2026).
- Halves lengthened from the baseline's 20 minutes to 25 minutes (carried forward unchanged
  into 2026); halftime set to 2 minutes (superseded by 2026's 5 minutes).
- Timeouts increased from the baseline's 1-per-half to 2-per-half (carried forward unchanged
  into 2026); added the timeout-for-rules-clarification mechanic and a 30-second clock runoff
  for an illegal timeout called with under 2:00 remaining (superseded by 2026's differently-
  worded 10-second version — see Open Issue OI-2).
- Introduced the 2-puck system, rush-line distances by division (7 yd JV / 10 yd
  Freshman-Peewee — carried forward unchanged into 2026), the "failed snap" penalty concept,
  and a full officiating-mechanics section (crew positioning, rules-debate procedure,
  progressive enforcement philosophy).
- 4th-down go/punt declaration introduced for FR/JV, with Peewee exempted (automatic
  4-then-4 down progression, no punt option) — 2026 broadens punting to any down without
  explicitly restating the Peewee exemption (see Open Issue OI-1).
- Clarified illegal-forward-pass includes any part of the passer's (or handoff recipient's) foot
  crossing the LOS.
- Clarified ball-spotting ("tackle spot") and forward-progress mechanics matching the baseline,
  restated for officiating clarity.

This document is retained in `sources/league-rules/lancaster-ny/2024/` for historical reference
and to trace where 2026 mechanics originated, but is **not authoritative** for current play —
`rulebook.md` reflects v2026.1 (layered on v0) as current.

---

## v0 — USA Football ADM Flag Rulebook (national baseline)

**Sources:** `sources/base-rules/usa-football-flag-rulebook.md`

The starting baseline: 3 downs to cross midfield / 3 more to score, 20-minute halves (40 minutes
total), 1 timeout per half, uniform 7-yard rush line for all divisions, coin-toss/escalating-stakes
overtime format restricted to playoff games, non-returnable conversion interceptions,
"encouraged" (not mandatory) mouthguards, and the core mechanics (forward progress, flag
guarding, no-run zones, dead-ball conditions, penalty categories) that both Lancaster league
documents build on rather than replace outright.

Cross-checked against the NFL FLAG "condensed field rules" one-pager
(`sources-base-rules` — see README) with no material inconsistencies found; the condensed
version is not separately versioned here since it added no new information.

---

## Pending — Not Yet Released

**4th-Down Decision Clock** (custom house rule, proposed by the league, not yet in an official
document): coach gets ~5 seconds to declare go-for-it vs. punt on 4th down. See
`sources/league-rules/lancaster-ny/2026/custom-additions.md`, `rulebook.md` §5.3, and Open
Issue OI-1. Do not treat as in force until finalized and merged into a `v2026.2` (or `v2027.1`)
entry here.
