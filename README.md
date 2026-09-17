# Logic Royale

A battle-royale reasoning game for B.Tech students. Free Fire mechanics mapped onto
logical-reasoning and problem-solving drills.

Single self-contained HTML file. No build step, no dependencies.

## The core idea

A right answer alone scores almost nothing. After every correct answer the player must
also pick the **key insight** — the actual reason the answer is right — from three
plausible candidates. Right insight banks a 1.6x multiplier. This is what stops the
game degrading into fast guessing.

## Mechanics

| Free Fire | Logic Royale |
|---|---|
| Shrinking safe zone | Per-round timer, 60s down to 22s |
| Storm damage | 6 HP per round from zone 7 |
| Headshot | Answer inside 40% of the clock, 2 extra eliminations |
| Loot crates | Hint, Fifty-fifty, Time freeze, Gloo wall, Medkit (rarity tiered) |
| Character skills | Deducer, Speedster, Analyst, Tank |
| Rank tiers | Bronze to Heroic, persisted in localStorage |

## Question bank

24 questions across number and letter series, blood relations, syllogisms,
coding-decoding, direction sense, seating arrangement, clocks, Venn diagrams,
data sufficiency, truth-teller puzzles, number theory — plus CSE-flavoured items:
pseudocode tracing, recursion tracing, Big-O, XOR identities, off-by-one errors.

Every question carries a worked explanation shown in the post-match replay.

## Run it

Open `index.html` in any browser.
