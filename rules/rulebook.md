# Lancaster NY Flag Football Rulebook

**Current through:** 2026 season (see `changelog.md` for version history)

## How to use this rulebook

This is the single authoritative statement of playing rules for Lancaster NY Flag Football. It
consolidates:

- The USA Football ADM Flag Rulebook (national baseline)
- Lancaster NY's 2024 rules document
- Lancaster NY's 2026 General Rules & Guidelines, Coaches Cheat Sheet, and Penalty Buddy card

into one numbered rule set, in the style of an NFHS/NCAA rulebook. Raw source transcriptions
are preserved under `sources/` for provenance and are not themselves authoritative — if this
document and a source transcription ever disagree, **this document governs**, and the
disagreement should be logged as a bug (fix the rulebook or open an issue, don't silently trust
the source).

**Precedence when sources conflict:** the most recent Lancaster league document beats an
older Lancaster document, which beats the USA Football baseline. Where the league is silent on
a topic, the USA Football baseline fills the gap (e.g., roster size — see Rule 1.2). Every rule below
states its Revision History so you can see which source it came from and whether it has been
overridden.

Each rule follows this format:

> **X.Y Title**
> **Rule** — the actual, current, enforceable rule text.
> **Officials Notes** — how it's administered on the field.
> **Rationale** — why the rule exists, where useful.
> **Case Plays** — cross-references into `casebook.md`.
> **Revision History** — where the current text came from and what it replaced.

Penalty yardage/enforcement for fouls referenced in this rulebook is centralized in
`penalty-matrix.md` rather than repeated rule-by-rule — each rule links to the relevant matrix
entries instead of restating numbers, to avoid the exact duplication problem this rulebook is
designed to eliminate.

Unresolved contradictions and gaps are logged in **Appendix A: Open Issues** at the end of this
document rather than silently decided.

---

## Chapter 1 — Game Administration

### 1.1 Pregame and Coin Toss

**Rule** — Team captains meet at midfield for a coin toss before the game. The visiting team
calls the toss. The winner chooses offense or defense; the loser chooses direction. Deferring the
choice to the second half is not permitted. Possession changes to start the second half, going to
the team that started the game on defense; teams also change sides at halftime.

The same team that called the opening coin toss also calls the overtime coin toss, if the game
goes to overtime — see Rule 13.1.

**Officials Notes** — The primary official (in a two-official system) handles the coin toss. See
`officials-manual.md` §OM-2. See also Rule 1.5 for the equipment briefing given at the coin toss.

**Revision History**
- Confirmed — the visiting team's coin-toss-calling role carries over to overtime, if needed (see
  Rule 13.1).
- v2026.1 — Lancaster 2026 General Rules explicitly prohibits deferral ("NO DEFERRALS").
- v0 (baseline) — USA Football rulebook §1 gave the same coin-toss/possession structure
  without addressing deferral.

---

### 1.2 Rosters and Minimum to Play

**Rule** — The league does not specify a full roster minimum/maximum — only the on-field
format (5-a-side) is defined, and no cap or floor on total roster size is needed. A team must be
able to field at least 4 players to play a game; a team unable to field 4 players forfeits (see
Rule 4.5).

**Revision History**
- Confirmed — the user confirmed no league-specified roster min/max is needed, and set the
  4-player minimum-to-play/forfeit threshold. Formerly Open Issue OI-6; see Resolved Issues.
  This replaces the baseline's more elaborate 5–10 roster / start-with-5 / drop-to-4-on-injury
  structure, which is no longer used to fill this gap.
- v0 (baseline) — USA Football rulebook §5 previously filled this gap (superseded).

---

### 1.3 Equipment and Uniforms

**Rule**
- All players must wear a mouthguard at all times on the field (2026 tightens the baseline's
  "encouraged" language to mandatory).
- Home team wears the darker/primary color, away team the lighter/secondary color:
  - Co-ed: Home = Red, Away = Black
  - Girls: Home = Red, Away = White
  - Teams post which jersey they'll wear for a given game on SportsEngine.
- Jerseys must be tucked in at all times.
- Shoes required; cleats allowed, but cleats with exposed metal are prohibited.
- Players must remove all jewelry deemed hazardous by officials, and all hats/do-rags (winter
  beanies allowed).
- Shorts/pants with pockets or belt loops must be taped; games are not delayed for this.
- Flag belts must not be the same color as the player's shorts or pants.

**Officials Notes** — Flag belts should be checked pregame for legal positioning (front side of
the hip) and that the "third flag" / belt slack is secured so it can't be confused with a live flag —
see `officials-manual.md` §OM-1.

**Revision History**
- v2026.1 — Lancaster 2026 sets specific jersey colors by division and makes mouthguards
  mandatory (Coaches Cheat Sheet / General Rules).
- v2024.1 — Lancaster 2024 added the flag-belt pregame check and third-flag/slack guidance.
- v0 (baseline) — USA Football rulebook §3 (generic home-dark/away-light, cleat/jewelry/tuck
  rules, flag-belt color rule).

---

### 1.4 Coaches on the Field

**Rule** — The number of coaches permitted on the field and in the huddle is division-specific:

| Division | Coaches on field / in huddle |
|---|---|
| Peewee | 2 |
| Freshman | 1 |
| Girls Freshman | 1 |
| Girls JV | 1 |
| JV | 0 |
| Varsity | 0 |

Where permitted, coaches must be behind the deepest offensive and defensive players at the
snap and out of the action. Coaches may assist with pre-snap alignment to keep the game
moving but may not give additional instruction or call audibles once the huddle has broken.

**Rationale** — Younger/developmental divisions get more on-field coaching support; JV/Varsity
play without it, consistent with increasing player independence.

**Revision History**
- v2026.1 — Lancaster 2026 introduced the division-specific coach counts (General Rules /
  Cheat Sheet).
- v0 (baseline) — USA Football rulebook §8 gave a single undifferentiated rule (coaches allowed
  per division/need, behind the deepest player, no audibles). Superseded by the 2026 table for
  which divisions get coaches at all; the positioning/no-audible constraint still applies where a
  coach is present.

---

### 1.5 Coin Toss Equipment Briefing

**Rule** — At the coin toss, the official explains to whoever is present (team captains) that:
1. Mouthguards are required to take the field (see Rule 1.3).
2. Flags must be worn on the hips.
3. The "third flag" — the excess belt slack beyond the two live flags — must be tucked away and
   not left hanging loose.

This briefing **is** the flag-guarding warning — it satisfies the "teach then enforce" notice
requirement for third-flag positioning (see `officials-manual.md`'s enforcement philosophy)
before the game starts. No separate in-game warning for improperly tucked third-flag slack is
required.

**Consequence.** If a defender pulls a runner's third flag rather than a live flag, the runner is
ruled down (same as any legal flag pull), **and** a flag guarding penalty is assessed against the
offense — the loose third flag being available to pull is itself the flag-guarding violation (Rule
7.4), since it created confusion about which flag was live.

**Case Plays** — See `casebook.md` §CP-15.

**Revision History**
- Confirmed — the coin-toss equipment briefing (mouthguards, flag hip position, third-flag
  tucking) serves as the flag-guarding warning; pulling the third flag downs the runner and
  draws a flag-guarding penalty.
- v2024.1 — Lancaster 2024 established the third-flag/belt-slack concept as part of the pregame
  flag-belt check (see Rule 1.3, `officials-manual.md` §OM-1); this rule adds the coin-toss timing
  and the specific third-flag-pulled consequence, neither of which was previously specified.

---

## Chapter 2 — The Field

### 2.1 Field Dimensions

**Rule** — Field is 30 yards by 53⅓ yards, with two 10-yard end zones and a midfield
line-to-gain. Smaller fields may be used where space or tournament scheduling requires it.
Stepping on a boundary line is out of bounds.

**Revision History**
- v0 (baseline) — USA Football rulebook §4. No league override.

---

### 2.2 No-Run Zones

**Rule** — A no-run zone exists 5 yards before midfield and 5 yards before each end zone. All
plays run inside a no-run zone must be pass plays — a handoff followed by a run in the zone is
not permitted, even if the handoff itself is legal (this includes an RPO where the ball ends up
handed off/run rather than thrown). A no-run zone violation is a **loss of down** — see
`penalty-matrix.md`. No yardage is assessed; the ball stays at the spot.

Each offensive drive encounters exactly two live no-run zones: one before midfield (to gain the
first down) and one before the target end zone (to score). Once the offense's spot enters a
no-run zone, the pass-only requirement is **sticky for the remainder of that set of downs**: it
stays in effect until the offense achieves the first down, scores, or turns the ball over — even if
an intervening penalty (e.g., delay of game) happens to move the resulting spot back outside
the zone's yard-line boundary. The restriction is tied to having entered the zone this set of
downs, not to the exact yard line of the current snap.

**Rationale** — Prevents short-yardage power-running situations near the line-to-gain/goal line,
keeping the game pass-oriented. The penalty for violating it is a loss of down specifically (rather
than a replay-of-down penalty like Illegal Procedure) so a team can't deliberately eat a no-run-
zone violation as a free do-over and simply try the run again on the next snap. The "sticky"
treatment mirrors the existing PAT rule (Rule 4.2), where a penalty that moves the spot doesn't
change a conversion attempt's already-declared type (1-point vs. 2-point) — here too, a penalty
doesn't undo the fact that the drive is inside the no-run zone.

**Case Plays** — See `casebook.md` §CP-2 (change of possession spot when a drive stalls inside
the no-run zone) and §CP-12 (no-run zone violation via RPO, and the zone's stickiness across
downs and penalties).

**Revision History**
- Confirmed — no-run zone violation is its own foul: loss of down, no yardage. Previously the
  penalty for this foul was undefined in `penalty-matrix.md` despite the rule requiring one.
  Also confirmed the pass-only requirement is sticky for the set of downs once the zone is
  entered — it survives an intervening penalty even if that penalty's yardage happens to move
  the resulting spot outside the zone's yard-line boundary.
- v2026.1 — Lancaster 2026 restates the same 5-yard zones (General Rules, Cheat Sheet).
- v0 (baseline) — USA Football rulebook §4, §10.5. No material change; carried forward.

---

## Chapter 3 — Timing

### 3.1 Game Length and Clock

**Rule** — Games consist of two 25-minute halves on a continuous (running) clock, controlled by
the referee. The clock stops only for timeouts, and at the official's discretion (e.g., injuries).

**Revision History**
- v2026.1 — Halves lengthened from the baseline's 20 minutes to 25 minutes (unchanged from
  the 2024 document, which also specified 25-minute halves).
- v2024.1 — Lancaster 2024 set 25-minute halves, running clock, officials-discretion stoppage.
- v0 (baseline) — USA Football rulebook §6 specified 20-minute halves (40 minutes total).

---

### 3.2 Halftime

**Rule** — Halftime is 5 minutes.

**Revision History**
- v2026.1 — Lancaster 2026 General Rules: 5-minute halftime.
- v2024.1 — Lancaster 2024: 2-minute halftime (superseded).
- v0 (baseline) — USA Football rulebook §6: 1-minute halftime (superseded).

---

### 3.3 Play Clock and Delay of Game

**Rule** — A 30-second play clock starts when the official spots the ball, or after a "return to
play" whistle following a stoppage. The offense must snap the ball within that window. A team
receives one warning before a delay-of-game penalty is enforced; see `penalty-matrix.md` for
enforcement.

**Officials Notes** — The official is responsible for marking off the rush line as part of spotting
the ball, and should give a verbal reminder/countdown around the 20-second mark. Officials
should use discretion with younger divisions who may need more time to line up. See
`officials-manual.md` §OM-3.

**Case Plays** — See `casebook.md` §CP-1 (play starting after a clock stoppage — offense must
wait for the "return to play" whistle before starting its cadence).

**Revision History**
- v2026.1 — Lancaster 2026 restates the 30-second play clock (General Rules, Cheat Sheet).
- v2024.1 — Lancaster 2024 added the countdown/warning mechanic and the "return to play"
  whistle requirement.
- v0 (baseline) — USA Football rulebook §6.3.

---

### 3.4 Timeouts

**Rule** — Each team gets 2 timeouts per half, 30 seconds each. Unused timeouts do not carry
over to the second half. All timeouts are called by coaches.

A coach may use a timeout to question an official's ruling or ask for a clarification. If the
official's original ruling is upheld, the timeout is charged; if the ruling is corrected in the
coach's favor (or it was a legitimate question), the timeout may be refunded at the official's
discretion.

If a team calls a timeout with none remaining, a delay-of-game penalty is enforced. In addition,
a 10-second clock runoff is enforced if the loss of time is disadvantageous to the team calling
the timeout (i.e., the team calling the timeout would win the game if it ended when the runoff
ended). This replaces the 2024 document's version of this rule, which used a 30-second runoff
triggered only when the game clock was under 2:00 remaining — 2026 supersedes 2024 here (see
Resolved Issues, formerly OI-2).

**Officials Notes** — See `officials-manual.md` §OM-4 for the rules-clarification-via-timeout
procedure and how officials should apply discretion in refunding a timeout.

**Revision History**
- v2026.1 — Lancaster 2026 General Rules confirms 2 timeouts/half, 30 seconds each, no
  carryover.
- v2024.1 — Lancaster 2024 set 2 timeouts/half, 30 seconds each, and introduced the
  timeout-for-rules-clarification mechanic.
- v0 (baseline) — USA Football rulebook §6.4 specified 1 timeout per half (superseded).

---

### 3.5 Clock Stoppage, Restart, and Injuries

**Rule** — If a timeout is called, the clock stops and restarts at the snap of the next timed down
(a PAT/conversion attempt is an untimed down — if a coach calls timeout immediately after a
touchdown, the conversion attempt does not run the clock). The same restart-at-next-snap
principle applies to any other clock stoppage, and to the start of each half.

If a timeout is called after a touchdown (making the PAT an untimed down), the next timed
down is the receiving team's first offensive snap — described as **"1st and half way"**: a first
down where the line-to-gain is midfield, same as the standard structure in Rule 5.1. This applies
regardless of exactly where in their own half that team's possession starts (their own 5-yard
line, per the normal post-score restart spot, or any other spot in their own half per another rule)
— as long as the spot is on their side of midfield, the line-to-gain is midfield, and the clock
starts at that snap.

The clock is not stopped for penalty enforcement unless a timeout was separately called.

In the event of an injury, the clock stops and restarts once the injured player has left the field
and both teams are lined up and ready.

**Revision History**
- Confirmed — "1st and half way": after a timeout following a touchdown, the clock starts at the
  snap of the receiving team's next possession, which is a first down with the line-to-gain at
  midfield regardless of the exact starting spot within their own half.
- v2026.1 — Lancaster 2026 General Rules clarifies the untimed-down treatment of PATs after a
  timeout.
- v2024.1 — Lancaster 2024 established the stop/restart-at-next-snap mechanic and the penalty
  clock-stoppage rule.
- v0 (baseline) — USA Football rulebook §6.5–6.6 (injury clock handling).

---

## Chapter 4 — Scoring

### 4.1 Touchdown

**Rule** — A touchdown is worth 6 points.

**Revision History**
- v0 (baseline) — USA Football rulebook §7.1. Unchanged by any league document.

---

### 4.2 Point After Touchdown (PAT)

**Rule** — After a touchdown, the scoring team must declare a 1-point or 2-point conversion
attempt:
- **1 point**, from the 5-yard line, **pass only**.
- **2 points**, from the 10-yard line, run or pass.

Once declared, the decision cannot be changed except by using a charged timeout (baseline
rule; no league document overrides this).

Interceptions on a PAT/conversion attempt during **regular play** may be returned for 2 points by
the defense. This is a deliberate override of the baseline, which rules the play dead immediately
on a conversion interception with no return.

**Officials Notes** — Because this is a return-eligible situation under current league rules
(unlike the baseline), officials should not blow the play dead immediately on a PAT interception
— play continues until the intercepting player is downed, out of bounds, or scores.

**Case Plays** — See `casebook.md` §CP-3.

**Revision History**
- v2026.1 — Lancaster 2026 General Rules / Cheat Sheet explicitly makes PAT interceptions
  returnable for 2 points, overriding the baseline.
- v0 (baseline) — USA Football rulebook §7.2 and §12.6 (1/2-point structure; conversion
  interceptions dead immediately, no return — the "no return" portion is superseded).

---

### 4.3 Safety

**Rule** — A safety is worth 2 points, awarded when the ball carrier is declared down in their own
end zone (flag pulled, flag falls out, steps out of bounds, knee/arm touches the ground, or a
snapped ball lands in or beyond the end zone).

An **enforced** snap/exchange failure (Rule 7.5) that comes to rest in the offense's own end
zone is also a safety — this applies whenever the failure results in an actual loss of down, not
just for JV/Varsity: it's automatic for JV/Varsity (no free redos), and also applies to Peewee/
Freshman/Girls Freshman once their 2-per-half do-over allowance is used up. A failure that's
still within the do-over allowance is simply replayed from the original line of scrimmage and
cannot produce a safety, since nothing is enforced.

**Revision History**
- Confirmed — safety-on-end-zone-failure applies to any division once the snap/exchange
  failure is enforced (loss of down), not only JV/Varsity — it just happens to be automatic for
  JV/Varsity since they get no do-overs at all.
- v2026.1 — Lancaster 2026 introduced safety for a JV/Varsity botched-exchange-in-end-zone
  scenario specifically; generalized above to any enforced failure regardless of division.
- v0 (baseline) — USA Football rulebook §7.3.

---

### 4.4 Mercy Rule / Running Score

**Rule** — Once a team leads by 28 or more points, score is no longer kept for the remainder of
the game, and no further PAT attempts occur. The game continues in scrimmage mode.

**Revision History**
- v0 (baseline) — USA Football rulebook §7.4. Unchanged by any league document. (2024's
  condensed field-rules cross-check independently confirmed the same 28-point threshold.)

---

### 4.5 Forfeits

**Rule** — A forfeit is scored 28–0 for the winning team.

**Revision History**
- v0 (baseline) — USA Football rulebook §7.5. Unchanged.

---

## Chapter 5 — Series of Downs

### 5.1 Downs and Line-to-Gain

**Rule** — The offense gets **4 downs** to cross the line-to-gain (midfield), and, once across, **4
more downs** to score. This overrides the USA Football baseline's 3-down structure.

**Revision History**
- v2026.1 / v2024.1 — Lancaster 2024 and 2026 both independently specify a 4-down system;
  no change between them.
- v0 (baseline) — USA Football rulebook §1.3 specified 3 downs to cross midfield and 3 more to
  score (superseded).

---

### 5.2 Punting

**Rule** — The offense may elect to punt on any down. A punt moves the ball to the opponent's
5-yard line and changes possession. (This is distinct from the older 2024 rule, which restricted
the punt election to 4th down only — see Revision History.)

**Case Plays** — See `casebook.md` §CP-2.

**Revision History**
- v2026.1 — Lancaster 2026 General Rules broadens punting to any down.
- v2024.1 — Lancaster 2024 restricted the punt election to 4th down for FR/JV, and gave Peewee
  no punt option at all (automatic 4-down-then-4-down progression). Superseded for 2026, but
  see Open Issue OI-1 for whether the Peewee no-decision structure still holds.
- v0 (baseline) — No punting concept exists in the USA Football baseline.

---

### 5.3 Fourth-Down Declaration

**Rule** — On 4th down, before the snap, the offense must declare (by the coach, to the official)
whether it is going for the line-to-gain/score or electing to punt. This declaration requirement
(and the decision clock below) applies to **Freshman, JV, and Varsity**. Peewee has no 4th-down
decision to make — it simply continues automatically through a second set of 4 downs (see Rule
5.1), with no punt election and no decision clock.

The decision window is **not** a separate timer — it is carried inside the existing 30-second play
clock (Rule 3.3), which starts the moment the official declares "4th down." The coach must
communicate the go/punt decision to the official within that same 30-second window. If the
coach has not declared a decision before the play clock runs out, a delay-of-game penalty is
enforced (see `penalty-matrix.md`), at the official's discretion.

**Officials Notes** — When declaring 4th down, the official must also announce the time
remaining in the half at that moment, in the same breath as the down declaration. Enforcement
of the delay-of-game penalty for a missed 4th-down decision carries the same referee discretion
as any other delay-of-game situation (see `officials-manual.md`'s "teach then enforce"
philosophy) — it is not automatic on the first violation of a season.

**Revision History**
- Confirmed — 4th-down decision clock applies to Freshman, JV, and Varsity (not Peewee, which
  has no 4th-down decision at all, per the 2024 rule). Formerly Open Issue OI-1; see Resolved
  Issues.
- v2026.2 (pending formal write-up) — 4th-down decision clock confirmed as part of the existing
  30-second play clock (not a separate timer), starting at the official's declaration of 4th down;
  missed decision = delay of game, at official discretion; official must announce half time
  remaining when declaring 4th down.
- v2026.1 — Lancaster 2026 broadened the punt option to any down (Rule 5.2), but a 4th-down
  go/punt declaration is still the operative decision point in practice for FR/JV since the punt
  yardage/possession outcome is defined relative to "4th down" scenarios in the source
  documents.
- v2024.1 — Lancaster 2024 established the pre-snap declaration requirement for FR/JV, with
  Peewee exempted.

---

### 5.4 Failure to Convert / Change of Possession Spot

**Rule** — If the offense fails to reach the line-to-gain or fails to score, possession changes to
the opponent at the spot where the ball was declared down — **except** when that spot falls
within the no-run zone nearest the defending team's end zone, in which case the ball is instead
placed at the 5-yard line before possession changes.

All possession changes other than interceptions start on the new offense's 5-yard line if the
change happens via a stalled drive that began from a kickoff-equivalent spot; where a specific
failure-to-convert spot is defined above, that spot governs.

**Case Plays** — See `casebook.md` §CP-2 and §CP-13 (contrast with the interception spot rule,
Rule 9.3, which is never pushed out to the 5-yard line).

**Revision History**
- v2026.1 / v2024.1 — Both Lancaster documents independently state the same "placed at the
  5-yard line if within the no-run zone" exception.
- v0 (baseline) — USA Football rulebook §1.4–1.6 gives the general "all possession changes
  except interceptions start on the 5-yard line" rule; the league's no-run-zone exception is a
  refinement, not a contradiction.

---

### 5.5 Offensive Spot Foul After the Line to Gain Is Already Made

**Rule** — If the offense commits any spot foul (flag guarding, charging, screening/blocking, or
any other offensive spot foul — see `penalty-matrix.md`) after the ball carrier has already
crossed the line-to-gain on that same play, the first down still stands. The foul's penalty
yardage is assessed from the spot of the foul, same as it would be anywhere else, but it does not
take away the first down already earned.

The next line-to-gain becomes the goal line, and the no-run zone that applies is the 5-yard zone
before the goal line. The next play is "first down and goal."

This is not limited to flag guarding — it applies uniformly to any offensive spot foul in this
situation. (Formerly Open Issue OI-8; see Resolved Issues.)

**Case Plays** — See `casebook.md` §CP-5.

**Revision History**
- Confirmed — generalized from the flag-guarding-specific ruling to all offensive spot fouls: the
  first down is awarded regardless of foul, the next line-to-gain is the goal line, the no-run zone
  is the 5 yards before the goal line, and the next play is first down and goal.

---

## Chapter 6 — Snapping and Formations

### 6.1 Formations and Motion

**Rule** — The offense must have at least one player on the line of scrimmage (the center) and
up to four players on the line. The quarterback must be off the line of scrimmage and cannot run
the ball.

Multiple offensive players may go in motion before the snap, but only one may still be moving at
the moment of the snap; all others must be set. Motion must be parallel to the line of
scrimmage — no motion toward the line of scrimmage is permitted. A set player, or a player in
motion who moves toward the line of scrimmage, commits a false start.

**Revision History**
- v2026.1 — Lancaster 2026 restates the multiple-in-motion/one-at-snap rule.
- v0 (baseline) — USA Football rulebook §15. Formation minimums/QB-off-line and the false
  start definition are unchanged.

---

### 6.2 Snapping the Ball

**Rule** — The ball must be snapped with a rapid, continuous motion between the center's legs
to a player in the backfield, and must completely leave the center's hands, **except** Peewee
and Girls Freshman, who may side-snap as needed.

The ball must be snapped from contact with the ground at the spot where it was placed — in
practice, from on top of the puck marking the line of scrimmage, where a puck is used.

**Officials Notes** — See `officials-manual.md` §OM-1 for the 2-puck system (one puck marks
the line of scrimmage, the other the rush line).

**Case Plays** — See `casebook.md` §CP-4.

**Officials Notes** — A snap that fails this rule (not properly delivered through the legs/side-
snapped where not permitted, or not taken from ground contact) is treated identically to a
botched exchange — see Rule 7.5, which now covers both scenarios under one rule.

**Revision History**
- v2026.1 — Lancaster 2026 carved out the Peewee/Girls Freshman side-snap exception.
- v2024.1 — Lancaster 2024 established the puck-based snap-from-the-ground requirement.
- v0 (baseline) — USA Football rulebook §15.3 (snap must be a rapid continuous motion between
  the legs, ball must leave the hands).
- Merged — the separate 2024 "failed snap" penalty concept was folded into Rule 7.5 (Snap and
  Exchange Failures) as a single rule; see that rule's Revision History.

---

### 6.3 False Start

**Rule** — A set offensive player who moves, or a player in motion who moves toward the line of
scrimmage, commits a false start. See `penalty-matrix.md`.

**Revision History**
- v2026.1 — Lancaster 2026 enforcement: -5 yards, replay of down (overrides baseline's loss of
  down — see `penalty-matrix.md`).
- v0 (baseline) — USA Football rulebook §15.2, §17.v.

---

## Chapter 7 — Running the Ball

### 7.1 Handoffs

**Rule** — Only direct handoffs behind the line of scrimmage are permitted, in front of, behind,
or to the side of the ball carrier. Multiple handoffs on a single play are allowed, provided they
remain behind the line of scrimmage. A "center sneak" is not allowed — the QB may not hand off
to the center on the first handoff of a play.

**Revision History**
- v0 (baseline) — USA Football rulebook §10.3. Unchanged by any league document.

---

### 7.2 Prohibition on Laterals and Pitches

**Rule** — No laterals, pitches, or screen passes of any kind are permitted, at or behind the line
of scrimmage. Handoffs are the only legal backward/lateral ball movement.

**Rationale** — Keeps the game a straightforward handoff-or-forward-pass structure and avoids
the officiating complexity of live backward passes.

**Revision History**
- v2024.1 — Lancaster 2024 restated this explicitly ("NO LATERALS, NO SCREEN PASSES").
- v0 (baseline) — USA Football rulebook §10.4 ("Absolutely NO laterals of any kind").

---

### 7.3 Forward Progress

**Rule** — Forward progress is determined by the ball carrier's frontmost foot at the moment the
flag is pulled. If the runner is downed by a body part other than feet or hands touching the
ground, forward progress is the furthest-upfield downed body part (including feet, but not
hands). **The position of the ball never determines forward progress.**

**Diving.** If a runner dives forward, the ball is spotted where the dive **started**, not where the
runner lands — a dive earns no additional forward progress beyond the takeoff point. See Rule
7.4 for when diving is also a flag-guarding foul.

**Officials Notes** — The ball is spotted where the runner's feet were when the flag was pulled,
not where the ball itself is. See `officials-manual.md` §OM-5 (tackle-spot mechanics).

**Case Plays** — See `casebook.md` §CP-9.

**Revision History**
- Confirmed — a forward dive is spotted at its starting point, not the landing point.
- v2026.1 / v2024.1 — Both Lancaster documents restate the general forward-progress rule
  identically.
- v0 (baseline) — USA Football rulebook §10.1.

---

### 7.4 Leaving Feet and Flag Guarding by Runners

**Rule** — Runners may not leave their feet to advance the ball. Diving or jumping to avoid a flag
pull is flag guarding. Spinning is legal, but spinning out of control to avoid a pull is flag
guarding. A runner may leave their feet without penalty if clearly doing so to avoid a collision
with another player, rather than to avoid a flag pull.

**What counts as "jumping."** To be judged illegal jumping under this rule, the motion must be
**more vertical than horizontal**. A juke (lateral evasive footwork) is not jumping. Leaping
forward (a predominantly horizontal motion) is not considered jumping either. This
determination is left to official discretion on a play-by-play basis — there is no hard-and-fast
angle threshold.

Diving is addressed separately and is still flag guarding when done to avoid a flag pull,
regardless of the vertical/horizontal test above (see also Rule 7.3 for the diving forward-
progress spot rule).

Flag guarding also includes stiff-arming, lowering the elbow or head, blocking flag access with a
hand or arm, or covering the flags with the jersey. All jerseys must be tucked in before the play
begins; deliberately obstructed flags are flag guarding.

An untucked "third flag" (belt slack) is also flag guarding if a defender pulls it instead of a live
flag — see Rule 1.5, which is both the pregame warning for this and the rule for the resulting
down/penalty.

**Case Plays** — See `casebook.md` §CP-5 (flag guarding after the runner has already gained a
first down on the same play — governed by the general rule at §5.5), §CP-10 (jump vs. juke vs.
forward leap), and §CP-15 (third flag pulled).

**Revision History**
- Confirmed — "jumping" for flag-guarding purposes requires a predominantly vertical motion;
  juking and forward leaping don't count as jumping under this rule. Official discretion governs
  close calls.
- v0 (baseline) — USA Football rulebook §10.8–10.13, §14 originally listed diving, leaping, and
  jumping together as flag-guarding triggers with no vertical/horizontal distinction; refined as
  above. See `penalty-matrix.md` for the league's revised yardage on this foul.

---

### 7.5 Snap and Exchange Failures

**Rule** — A single rule now covers both a failed/bad snap (ball not properly delivered per Rule
6.2 — e.g., not taken from ground contact, or not delivered through the center's legs where
required) and a botched/fumbled handoff exchange. There are no live fumbles — the ball is dead
the instant it hits the ground. Both scenarios are enforced identically:

| Division | 1st–2nd occurrence per half | After cap | 
|---|---|---|
| Peewee, Freshman, Girls Freshman | Do-over, no loss of down/yardage (up to 2 per team per half) | Loss of down, no yardage loss |
| JV, Varsity | Loss of down, no yardage loss (no free redos) | — |

**Spot.** A do-over (within the free-redo cap) is replayed from the original line of scrimmage —
where the failed snap/exchange physically ended up is irrelevant, since the down is erased. Once
a failure is **enforced** (loss of down — automatic for JV/Varsity, or PW/Freshman/Girls Freshman
past their cap), the ball is spotted where it first touched the ground — the same general
dead-ball spotting rule as any other bad snap (Rule 11.2) — not wherever it subsequently rolled
or bounced to, and not reset back to the original line of scrimmage. "No loss of yardage" means
no *additional* penalty yardage is subtracted on top of that natural spot.

If an enforced snap/exchange failure comes to rest in the offense's own end zone under this
spotting rule, it is a safety (see Rule 4.3) — this can happen even when the original line of
scrimmage wasn't at the goal line, if the ball itself ends up there.

**Officials Notes** — The "2 free redos per half" allowance applies only in the divisions where it
has been declared to apply (Peewee, Freshman, Girls Freshman) — JV/Varsity get no free redos
for either a bad snap or a botched exchange, straight to loss of down.

**Case Plays** — See `casebook.md` §CP-4, §CP-14.

**Revision History**
- Confirmed — spot for an enforced snap/exchange failure is the point where the ball first
  touched the ground (Rule 11.2's general dead-ball spotting rule), not the original line of
  scrimmage and not wherever the ball rolled to afterward. This is what allows a safety even
  when the offense wasn't snapping from right at the goal line.
- Merged — the 2024 "failed snap" rule and the 2026 "botched exchange" rule are combined into
  this single rule at the user's direction: same underlying scenario (a failed ball transfer at the
  snap or handoff), same division-based 2-per-half allowance, one rule going forward. Formerly
  tracked as Open Issue OI-3; see Resolved Issues.
- v2026.1 — 2026 General Rules / Cheat Sheet introduced the "botched exchange" term and the
  division-based do-over table.
- v2024.1 — Lancaster 2024 introduced the "failed snap" term and penalty for a poorly-executed
  snap.

---

### 7.6 Offensive Players Without the Ball — No Blocking/Screening

**Rule** — No blocking or "screening" is allowed at any time. Once a play has crossed the line of
scrimmage via a pass or run, all offensive players without the ball must come to a complete
stop.

**Revision History**
- v2026.1 — Lancaster 2026 restates the complete-stop requirement explicitly.
- v0 (baseline) — USA Football rulebook §10.11–10.12.

---

## Chapter 8 — Passing

### 8.1 Forward Pass Requirements

**Rule** — All passes must be thrown from behind the line of scrimmage and must cross the line
of scrimmage, whether caught or not. A pass that does not cross the line of scrimmage is an
illegal forward pass, regardless of whether it's received. The passer may throw the ball away to
avoid a sack, but the throwaway must still cross the line of scrimmage to be legal.

**Officials Notes** — At junior/developmental levels, officials should use discretion for passes
that don't reach the line of scrimmage as long as the passer made an honest effort.

**Revision History**
- Confirmed — the ball itself (not just the passer's release point) must travel beyond the line of
  scrimmage for the pass to be legal; reaffirmed as still the operative rule.
- v0 (baseline) — USA Football rulebook §11.1. Unchanged in substance by any league
  document; see `penalty-matrix.md` for the league's current yardage on this foul.

---

### 8.2 Pass Clock

**Rule** — The passer has 7 seconds to release the ball once it is snapped (or, if handed off, the
7-second clock still governs the ball carrier's run-or-throw decision when there is no blitz). If the
ball is not released in time, the play is dead, the down is consumed, and the ball is returned to
the line of scrimmage. Once a ball has been handed off, the 7-second rule governs only if that
player intends to throw; the rush-line restriction (Rule 10.1) is separately lifted once the ball is
handed off.

**Officials Notes** — Officials keep an internal count, signaling the final seconds verbally (per
the baseline's basketball-style 3-second-call analogy) so the passer can hear it.

**Revision History**
- v2026.1 — Lancaster 2026 clarifies the 7-second clock also governs a ball carrier's run-or-pass
  decision after a handoff when unblitzed.
- v0 (baseline) — USA Football rulebook §11.3.

---

### 8.3 Shovel Passes

**Rule** — Shovel passes are legal but must be received beyond the line of scrimmage, same as
any other forward pass.

**Revision History**
- v0 (baseline) — USA Football rulebook §11.2. Unchanged.

---

### 8.4 Illegal Forward Pass

**Rule** — A forward pass is illegal in either of these cases:
1. The pass does not cross the line of scrimmage (received or not) — see Rule 8.1.
2. The passer's foot has crossed the line of scrimmage at release. **Any part of the passer's toe
   touching the line of scrimmage counts as having gone over it** — contact with the line itself is
   enough to make the pass illegal; the foot does not need to be fully past the line.

This applies equally to a player who received a handoff and then throws — their foot must stay
strictly behind the line of scrimmage (not touching it) at release.

See `penalty-matrix.md` for enforcement.

**Case Plays** — See `casebook.md` §CP-6 (passer's foot crossing the LOS during a passing play,
including a player who received a handoff and then throws).

**Revision History**
- Confirmed — the passer's toe merely touching the line of scrimmage counts as crossing it, not
  just fully passing over it.
- v2024.1 — Lancaster 2024 clarified that this includes any part of the passer's (or a
  handoff-recipient's) foot crossing the line of scrimmage during the pass attempt.
- v0 (baseline) — USA Football rulebook §11.1.a.

---

## Chapter 9 — Receiving

### 9.1 Eligible Receivers

**Rule** — All offensive players are eligible to receive a pass, including the quarterback if the
ball was handed off behind the line of scrimmage first.

**Revision History**
- v0 (baseline) — USA Football rulebook §12.1. Unchanged.

---

### 9.2 Simultaneous Possession

**Rule** — If an offensive and defensive player gain possession simultaneously, possession is
awarded to the offense.

**Revision History**
- v0 (baseline) — USA Football rulebook §12.4. Unchanged.

---

### 9.3 Interceptions

**Rule** — Interceptions change possession at the point of the interception and are returnable —
during regular play, for 6 points if returned to the end zone; on a PAT/conversion attempt, for 2
points if returned to the end zone (see Rule 4.2 for the league's override of the baseline's
no-return conversion rule).

Interceptions are the only change of possession that does not restart at the 5-yard line. If the
interception is not returned for a score, the new offense starts wherever the return's forward
progress ends (Rule 7.3) — not at the original interception spot if the ball was advanced, and
**not artificially moved out to the 5-yard line even if that spot is inside the intercepting team's
own 5-yard line.** This is a deliberate contrast with Rule 5.4's no-run-zone turnover-on-downs
treatment, which does push the ball out to the 5-yard line — that adjustment applies specifically
to a turnover on downs inside the no-run zone, not to interceptions.

**Case Plays** — See `casebook.md` §CP-13.

**Revision History**
- Confirmed — an interception's return, if not scored, is spotted at the end of the return's
  forward progress, with no 5-yard-line floor, even deep in the intercepting team's own territory.
  Corrected imprecise earlier wording that described this as "the spot of the interception,"
  which doesn't account for a returned interception advancing past the original catch point.
- v2026.1 — Lancaster 2026 makes conversion-attempt interceptions returnable (see Rule 4.2).
- v0 (baseline) — USA Football rulebook §12.5–12.6 (interception spot rule unchanged; the
  no-return conversion rule is superseded).

---

### 9.4 Successful Reception / Inbounds

**Rule** — For a receiver catching the ball in the air, the result depends on the first foot down:

- **First foot lands out of bounds** — incomplete pass.
- **First foot lands inbounds** — complete pass (regardless of what the other foot does next).
- **Both feet touch the ground simultaneously** — complete pass.

This also applies if a player completes a catch and has at least one foot inbounds before
subsequently going out of bounds.

**Case Plays** — See `casebook.md` §CP-11.

**Revision History**
- Confirmed — explicit first-foot-down logic for in-air catches: first foot out of bounds is
  incomplete; first foot inbounds is complete; simultaneous two-foot landing is complete.
- v0 (baseline) — USA Football rulebook §9.3, §12.3 established the general "at least one foot
  inbounds" principle; the first-foot-down and simultaneous-landing detail above refines it
  rather than contradicting it. Restated identically by Lancaster 2026.

---

## Chapter 10 — Rushing the Passer

### 10.1 Rush Line Distances by Division

**Rule** — Pass rushers must stay behind a rush line whose distance from the line of scrimmage
depends on division:

| Division | Rush line distance |
|---|---|
| Peewee, Freshman (and Girls Freshman, by extension) | 10 yards |
| JV, Varsity | 7 yards |

The rusher must keep both feet behind the rush-line puck until the ball is released or handed
off. Any number of defenders may rush, as long as they stay behind the applicable rush line.

**Officials Notes** — In Peewee/Freshman, the blitzer must raise a hand and identify themselves
as the rusher before the play. In these divisions, non-blitzing defenders must additionally stay at
least 5 yards back from the line of scrimmage until the snap (see Rule 10.2) — the rush-line
restriction applies specifically to the identified blitzer.

**Case Plays** — See `casebook.md` §CP-7.

**Revision History**
- v2026.1 / v2024.1 — Both Lancaster documents independently specify 7 yards for JV and 10
  yards for Freshman/Peewee, overriding the baseline's uniform 7-yard rule across all divisions.
  2026 additionally requires the Freshman/Peewee blitzer to self-identify.
- v0 (baseline) — USA Football rulebook §13.1 specified a uniform 7-yard rush line for all
  divisions (superseded for Freshman/Peewee).

---

### 10.2 Defensive Alignment Restrictions

**Rule** — In Peewee, Freshman, and Girls divisions, all non-blitzing defenders must line up at
least 5 yards back from the line of scrimmage. They may advance to the line of scrimmage at the
snap but may not cross it before the snap. Only the designated blitzer is permitted behind the
line of scrimmage before the ball is released or handed off.

In JV and Varsity, defensive players may line up anywhere.

**Revision History**
- v2026.1 — New in the 2026 General Rules / Cheat Sheet. No baseline or 2024 equivalent; the
  baseline's alignment rules did not distinguish blitzers from other defenders in this way.

---

### 10.3 Legal and Illegal Rush

**Rule** — A legal rush is any rush that begins from at or behind the applicable rush line (Rule
10.1), or any rush from anywhere on the field after the ball has been handed off. A rusher who
leaves the rush line early (before the snap, or before a handoff/pass) may return to the rush line,
reset, and then legally rush. There is no illegal-rush penalty once the ball has been handed off.

It is an illegal rush if the rusher leaves the rush line before the snap and crosses the line of
scrimmage before a handoff or pass occurs. See `penalty-matrix.md` for enforcement.

Rushers rushing the quarterback may attempt to block a pass, but may make **no contact** with
the passer in any way — blocking (or attempting to block) the pass and then contacting the
passer is roughing the passer.

The offense may not impede the rusher's clear path to the passer. If the offense's path is
occupied by a moving offensive player, avoiding the rusher is the offense's responsibility and
any disruption/contact is an impeding-the-rusher foul on the offense. If the offensive player does
not move after the snap, avoiding contact becomes the rusher's responsibility.

**Revision History**
- v2026.1 — Lancaster 2026 requires both feet behind the puck (refinement, not a substantive
  change from the baseline's "7/10 yards from the LOS" framing).
- v0 (baseline) — USA Football rulebook §13.

---

### 10.4 Sacks

**Rule** — A sack occurs when the quarterback's flags are pulled behind the line of scrimmage;
the ball is placed where the quarterback's feet were at the moment of the pull. A sack in the
offense's own end zone is a safety.

**Revision History**
- v0 (baseline) — USA Football rulebook §13.6. Unchanged.

---

## Chapter 11 — Flag Pulling and Dead Ball

### 11.1 Legal Flag Pull

**Rule** — A legal flag pull requires the ball carrier to be in full possession of the ball. Defenders
may dive to pull flags but may not tackle, hold, or run through the ball carrier. Stripping or
pulling the ball itself from the carrier's possession is illegal at all times. A defender may not
intentionally pull the flags of a player who is not in possession of the ball.

**Revision History**
- v0 (baseline) — USA Football rulebook §14. Unchanged.

---

### 11.2 Dead Ball Declarations

**Rule** — A play is dead when any of the following occurs:
- The ball hits the ground (including a bad snap — the ball is then placed where it hit the
  ground)
- The ball carrier's flag is pulled, or falls out on its own (ball placed where the flag lands)
- The ball carrier steps out of bounds
- A touchdown, PAT, or safety is scored
- Any part of the body other than feet or hands touches the ground
- A receiver catches the ball while in possession of one or no flags
- The 7-second pass clock expires
- An inadvertent whistle is blown (see Rule 11.4)
- The ball carrier's knee or arm contacts the field, or the ball carrier leaves their feet (Lancaster
  2026 phrasing; overlaps with several baseline items above but is stated as a standalone
  ball-leaves-feet condition)

**Officials Notes** — There are no fumbles/live loose balls under any current league rule — the
ball is dead the instant it touches the ground, full stop.

**Revision History**
- v2026.1 — Lancaster 2026 restates dead-ball conditions with a "ball carrier leaves their feet"
  clause.
- v0 (baseline) — USA Football rulebook §9.7.

---

### 11.3 Ball Spotting

**Rule** — The ball is always spotted according to where the runner's feet were when the flag
was pulled — never according to where the ball itself is. See Rule 7.3 (forward progress).

**Revision History**
- v2024.1 — Lancaster 2024 restated this as a "tackle spot" mechanic for officials.
- v0 (baseline) — USA Football rulebook §10.1.

---

### 11.4 Inadvertent Whistle

**Rule** — If an official blows an inadvertent whistle, the offense has two options: (a) take the
ball at the spot when the whistle blew, with the down consumed, or (b) replay the down from the
original line of scrimmage.

**Revision History**
- v0 (baseline) — USA Football rulebook §9.8. Unchanged.

---

## Chapter 12 — Player and Fan Conduct

### 12.1 Unsportsmanlike Conduct and Ejections

**Rule** — Intentional tackling, elbowing, cheap shots, blocking, or any unsportsmanlike act
results in the game being stopped and the player ejected, at the referee's discretion. No appeals
are considered. Offensive or confrontational language draws one warning from the referee;
continued conduct results in ejection.

**Revision History**
- v0 (baseline) — USA Football rulebook §16. Unchanged in substance; see `penalty-matrix.md`
  for the league's current yardage.

---

### 12.2 Personal Fouls and Progressive Discipline

**Rule** — Unnecessary roughness is a safety-related personal foul involving excessive force or
unnecessary contact — including but not limited to tackling, pushing, or dragging a player to the
ground; lowering the shoulder; intentionally running into a player while making no attempt to
pull the flag; tripping; or pushing a player out of bounds.

A player's first personal foul in a game is treated as a warning. A second personal foul by the
same player results in ejection.

**Revision History**
- v2026.1 — New in Lancaster 2026: explicit unnecessary-roughness definition and the
  first-foul-warning / second-foul-ejection structure. No baseline or 2024 equivalent of this
  specific progressive-discipline mechanic (the baseline's ejection standard in Rule 12.1 is
  more general/discretionary).

---

### 12.3 Fan Conduct

**Rule** — Fans must cheer for their players rather than harass officials or opposing teams, keep
comments clean and profanity-free, and compliment all players rather than singling one out.
Fans and their equipment (coolers, chairs, tents) must stay a minimum of 10 yards off the field in
the end zone area, and out of the administration zone (reserved for league administration,
officials, medical personnel, coaches, and players). All trash must go in designated cans.

**Revision History**
- v0 (baseline) — USA Football rulebook §16.6–16.7. Unchanged.

---

## Chapter 13 — Overtime

### 13.1 Overtime Format

**Rule** — Any game tied at the end of regulation goes to overtime — regular season and
playoffs alike (this league does not restrict overtime to playoff games only). Each team gets one
play from the 5-yard line to pass for a 1-point conversion.

- If one team succeeds and the other does not, the team that scored wins immediately.
- If both succeed, or both fail, both teams move to the 10-yard line for another round of
  1-point pass attempts, and the process repeats (returning to the 10-yard line each
  subsequent round) until a winner emerges.

**Coin toss.** The same team that called the opening coin toss (Rule 1.1 — the visiting team)
also calls the overtime coin toss. There is **one toss, no re-toss**. The winner decides whether
to attempt first or second — for the entire overtime, not re-decided round to round. This is a
single up-front call, not the alternating offense/defense choice used at the start of regulation.

**End zone and setup.** Officials decide which end zone overtime is played in — there is no coin-
toss element to this choice. Before the first attempt, officials should explain the overtime
format to both teams and to fans at that end zone.

**Officials Notes** — This is a full replacement of the baseline overtime format, not a layered
modification — see Revision History. Do not mix the two formats. Since both teams always
attempt a conversion each round (no defense on the field for the other team's attempt), the
overtime coin toss decides attempt order only, not an offense/defense role.

**Case Plays** — See `casebook.md` §CP-8.

**Revision History**
- Confirmed — overtime coin toss: same team that called the opening toss calls it; one toss, no
  re-toss; winner picks first or second for the whole overtime. Officials (not a toss) choose the
  end zone, and must explain the format to both teams and to fans there.
- v2026.1 — Lancaster 2026 General Rules introduces this shootout-style format explicitly "to
  avoid ties for standings," replacing the baseline format entirely.
- v0 (baseline) — USA Football rulebook §6.7 used a coin-toss-driven, alternating offense/
  defense-choice format with escalating 1-vs-2-point options starting at the 5-yard line
  (1-point) and 10-yard line (2-point), and restricted overtime to playoff games only. **Fully
  superseded** for the 2026 season, including the playoff-only restriction — confirmed by the
  user that this league always plays overtime, regardless of whether it's a regular-season or
  playoff game. Formerly Open Issue OI-7; see Resolved Issues.

---

## Appendix A — Open Issues

Unresolved ambiguities, contradictions, and gaps identified while consolidating the source
documents. **None of these have been resolved by inventing a rule** — only by an explicit
decision from the user. Each open item should be discussed with the league and, once settled,
folded back into the relevant rule above with an updated Revision History entry (moved to
"Resolved Issues" below rather than deleted).

*No open issues at this time* — see "Resolved Issues" below for the full history. New
ambiguities/contradictions/gaps identified in future revisions get logged here, numbered
continuing from OI-9.

---

## Resolved Issues

Formerly open, now settled by the user. Kept here (rather than deleted) so the reasoning behind
the current rule text stays traceable.

### OI-8 (Resolved) — Spot Foul on Offense After the Line to Gain Is Already Made

Was: unclear whether the flag-guarding-specific ruling (first down stands, penalty yardage
assessed from the spot, next play is first down and goal) generalizes to any offensive spot foul
in the same situation, or is unique to flag guarding. **Resolution:** it generalizes — see Rule 5.5.
Any offensive spot foul (flag guarding, charging, screening/blocking, etc.) committed after the
ball carrier has already crossed the line-to-gain on that play gets the same treatment: first down
awarded, penalty yardage assessed from the spot, next line-to-gain is the goal line (no-run zone
= 5 yards before the goal line), next play is first down and goal.

### OI-1 (Resolved) — Fourth-Down Decision Clock: Division Scope

Was: unclear whether the 4th-down decision clock (Rule 5.3) applies to all divisions or only some,
given Peewee's 2024 exemption from any 4th-down decision at all. **Resolution:** applies to
Freshman, JV, and Varsity. Peewee remains exempt — no 4th-down decision, no decision clock.

### OI-2 (Resolved) — Illegal-Timeout Clock Runoff

Was: 2024 used a 30-second runoff triggered by "under 2:00 remaining"; 2026 uses a 10-second
runoff triggered by "disadvantageous to the team calling the timeout." **Resolution:** the 2026
document supersedes the 2024 document outright — no reconciliation needed. Rule 3.4 uses the
2026 wording/values as-is.

### OI-3 (Resolved) — "Failed Snap" vs. "Botched Exchange"

Was: unclear whether the 2024 "failed snap" rule and the 2026 "botched exchange" rule were the
same scenario renamed, or two distinct rules that should both stay in force. **Resolution:** the
user directed that they be combined into one rule going forward — see Rule 7.5 (Snap and
Exchange Failures), which now covers both a bad/failed snap and a fumbled handoff exchange
under a single division-based do-over table (2 free redos per half in the divisions where that has
been declared to apply — Peewee, Freshman, Girls Freshman; no free redos for JV/Varsity).

### OI-5 (Resolved) — 2024 Officiating Mechanics

Was: the 2024 document's officiating mechanics (2-puck system, primary/line-judge crew role
split, midfield rules-debate procedure, "teach-then-enforce" philosophy, timeout-for-
clarification mechanic) weren't restated in any 2026 document — unclear whether they were
dropped or just carried forward silently. **Resolution:** the user confirmed to keep the 2024
versions. `officials-manual.md` stands as-is, no changes needed.

### OI-6 (Resolved) — Roster Size

Was: no 2026 document states a roster minimum/maximum, only the on-field format (5-a-side).
**Resolution:** the user confirmed no roster min/max needs to be specified at all — the relevant
threshold is a 4-player minimum to play a game, below which the team forfeits. See Rule 1.2 and
Rule 4.5. This replaces the baseline's 5–10 roster / drop-to-4-on-injury structure, which is no
longer used to fill this gap.

### OI-7 (Resolved) — Overtime Scope

Was: unclear whether the 2026 shootout overtime format applies to all games, or only playoffs
(the baseline restricted it to playoffs). **Resolution:** the user confirmed the league always
plays overtime, regular season and playoffs alike. See Rule 13.1.
