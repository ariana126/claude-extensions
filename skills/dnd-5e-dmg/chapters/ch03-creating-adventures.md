# Chapter 3: Creating Adventures

## Core Idea
Every adventure needs a credible threat, heroes whose choices matter, and a mix of exploration/social/combat content — and the DMG gives you an exact, load-bearing formula (XP thresholds × encounter multipliers) for calibrating combat difficulty instead of guessing.

## Frameworks Introduced
- **Combat Encounter Difficulty math** (the single most important mechanical framework in the book):
  1. Look up each character's XP threshold for Easy/Medium/Hard/Deadly at their level (see Reference Tables).
  2. Sum thresholds across the party for each category → the party's 4 XP thresholds.
  3. Sum the XP value of all monsters in the encounter.
  4. Multiply that sum by the Encounter Multiplier based on monster *count* (more monsters = more attacks/round = disproportionately harder).
  5. Compare the adjusted XP to the party's thresholds; the highest threshold it meets or exceeds is the difficulty.
  - When to use: every combat encounter you design or evaluate, not just "boss fights."
  - How: see Reference Tables for exact XP-by-level and multiplier values.
- **The Adventuring Day budget**: sum each character's "Adjusted XP per Day" (Reference Tables) across the party to get a full day's XP budget; a typical day supports **6-8 medium-to-hard encounters**, with **~2 short rests** spaced roughly 1/3 and 2/3 through the day. More easy encounters fit; fewer deadly ones do.
  - When to use: pacing a dungeon crawl or travel day so resource attrition (spell slots, HP) feels meaningful without overwhelming the party.
- **Multipart encounters**: treat each wave of a staged fight as its own encounter for difficulty purposes — but if a wave's adjusted XP exceeds 1/3 of the day's total XP budget, the whole multipart fight will play *harder* than the sum of its parts, because the party can't short-rest between waves.
- **Situational modifiers**: a drawback the party has but the enemy doesn't bumps difficulty up one step (Easy→Medium, etc.); a benefit only the party has bumps it down one step; a benefit and a drawback cancel out. (Surprised, no cover, blinded, immobilized, ongoing unequal damage are the drawback examples given.)
- **Location-based adventure build order** (6 steps, order flexible): (1) identify party goals via Dungeon/Wilderness/Other Goals tables, (2) identify villain/allies/patrons via d20/d12 tables, (3) flesh out location (→ Ch 5), (4) pick an introduction (d12 table), (5) pick a climax (d12 table), (6) plan encounters.
- **Event-based adventure build order** (8 steps): (1) start with a villain, (2) determine the villain's actions, (3) determine the party's goals, (4) identify important NPCs, (5) anticipate the villain's reactions to setbacks, (6) detail key locations, (7) choose introduction/climax, (8) plan encounters. Use when *what happens* matters more than *where*.
- **Mystery adventure add-ons**: layer Victim (give them a relationship to the villain AND to a PC), Suspects (a closed circle, several with unrelated secrets so innocents look guilty too), and Clues (over-provide — redundant clues so missing one doesn't stall the whole mystery) onto the event-based skeleton.
- **Intrigue adventure add-ons**: works with No Villain (skip straight to party goals, invest in NPC relationships), Single Villain, or Many Villains (spend most effort on step 1-2, since foiling one villain's plan can advance/block another's automatically). Track stakes with an **Influence** resource — either spent like Inspiration (grant it, spend for advantage) or tracked like Renown (Ch 1) per faction/NPC.

## Key Concepts
- **Adventure hook** — the concrete inciting incident that gets characters moving (attack, discovery, summons); should be exciting and specific, not vague.
- **Location-based vs. event-based adventure** — the former is organized around a place (dungeon key), the latter around a villain's unfolding plan (where is secondary).
- **Multipart encounter** — a fight split into waves the party can't short-rest between; disproportionately harder than its XP total suggests.
- **Framing event** — a scheduled in-world happening (coronation, eclipse, festival, trial) used to structure an entire adventure or just kick one off.
- **Moral quandary** — a single unavoidable, non-combat-resolvable choice (Ally/Friend/Honor/Rescue/Respect flavors) that forces a values trade-off, not a tactical one.

## Mental Models
- Think of an encounter as needing a **transparent objective**, not just a stat block to fight — "Make Peace," "Protect," "Retrieve," "Run a Gauntlet," "Sneak In," "Stop a Ritual," "Take Out a Single Target" are all valid non-annihilation win conditions.
- Random encounters aren't padding — they're a **toolbox for pacing and tone**: use them to create urgency (avoid dawdling), establish atmosphere (thematically linked creatures), drain resources, occasionally help the party, foreshadow, or reinforce campaign themes. If they're not doing one of these jobs, cut them.
- Treat "familiar tropes" as a feature, not a bug — the twist is what earns them (the king in disguise, the "crazy wizard" who's actually an illusion). Subversion needs a baseline of familiarity to subvert.

## Anti-patterns
- **Ignoring challenge rating traps at low level**: a CR 2 ogre one-shots a 1st-level wizard; a CR 13 rakshasa is immune to spells of 6th level or lower, neutering casters below 13th level. XP budget alone can understate real lethality — sanity-check single high-CR monsters against the party's actual level, not just the math.
- **Random encounters that kill the party**: acceptable difficulty for a random encounter is capped at "a single monster with CR ≤ party level" or an XP-budget Easy/Medium/Hard result — never build a random table entry meant to be unbeatable.
- **Railroading**: an adventure where the outcome is a foregone conclusion regardless of player choices breaks "Heroes Who Matter" — always design so a major villain fight can plausibly go the party's way (or badly) based on their play.
- **Using the "ally betrays you" climax too often**: explicitly flagged in the book itself as a climax to use "carefully, and don't overuse."

## Reference Tables

**XP Thresholds by Character Level** (per-character; sum across party)
| Level | Easy | Medium | Hard | Deadly |
|---|---|---|---|---|
| 1 | 25 | 50 | 75 | 100 |
| 3 | 75 | 150 | 225 | 400 |
| 5 | 250 | 500 | 750 | 1,100 |
| 8 | 450 | 900 | 1,400 | 2,100 |
| 10 | 600 | 1,200 | 1,900 | 2,800 |
| 12 | 1,000 | 2,000 | 3,000 | 4,500 |
| 15 | 1,400 | 2,800 | 4,300 | 6,400 |
| 17 | 2,000 | 3,900 | 5,900 | 8,800 |
| 20 | 2,800 | 5,700 | 8,500 | 12,700 |
*(full table runs every level 1-20; values scale roughly geometrically — see book for every row.)*

**Encounter Multipliers** (by monster count, standard 3-5 PC party)
| # Monsters | ×1 | ×1.5 | ×2 | ×2.5 | ×3 | ×4 |
|---|---|---|---|---|---|---|
| Count | 1 | 2 | 3-6 | 7-10 | 11-14 | 15+ |
*(party <3: bump one multiplier tier higher; party 6+: bump one tier lower — solo monster vs. 6+ PCs uses ×0.5.)*

**Adventuring Day XP** (per character, sample levels)
| Level | XP/day | Level | XP/day |
|---|---|---|---|
| 1 | 300 | 11 | 10,500 |
| 3 | 1,200 | 13 | 13,500 |
| 5 | 3,500 | 15 | 18,000 |
| 8 | 6,000 | 17 | 25,000 |
| 10 | 9,000 | 20 | 40,000 |

**Worked example from the book**: Party of three 3rd-level + one 2nd-level PCs → thresholds Easy 275 / Medium 550 / Hard 825 / Deadly 1,400. Encounter of 1 bugbear + 3 hobgoblins (500 XP raw, 4 monsters → ×2 multiplier) = 1,000 adjusted XP → falls between Hard (825) and Deadly (1,400) → rated **Hard**.

## Worked Example
Building a Medium encounter for the same party (thresholds above, Medium = 550): pick a single CR 3 monster worth 700 base XP (single monster → ×1 multiplier) — adjusted XP 700 falls between Medium (550) and Hard (825), so it reads as Medium-leaning-Hard. Alternative: a pair of 200-XP dire wolves, count 2 → ×1.5 multiplier → adjusted 600 XP, cleanly Medium. This mirrors the book's own worked example and shows why monster *count* (not just raw XP) drives the multiplier choice — two weaker monsters can hit the same difficulty band as one stronger one at a different XP cost.

## Key Takeaways
1. Use the 5-step XP-threshold-and-multiplier process for every combat encounter — don't eyeball difficulty.
2. Budget a full adventuring day at 6-8 medium/hard encounters with ~2 short rests, and treat multipart fights as harder than their summed XP if any wave exceeds 1/3 of the day's XP budget.
3. Give every encounter — combat or not — a transparent objective beyond "fight until 0 HP."
4. Random encounters must justify themselves (urgency, atmosphere, attrition, help, foreshadowing, theme) or should be cut.
5. Layer Mystery (Victim/Suspects/Clues) or Intrigue (Villains/Influence) modules onto the standard event-based build order rather than treating them as separate systems.
6. Use situational benefit/drawback stacking (±1 difficulty step each, capped at cancel-out) to let terrain and circumstance meaningfully shift a fight's real difficulty from its XP math.

## Connects To
- **Ch 1**: Tiers of Play sets which monster CRs and magic items are "in bounds" for a given XP-threshold encounter.
- **Ch 4**: villain/ally/patron NPC tables here hand off directly into NPC creation guidance.
- **Ch 5**: location-detail step (step 3) is fully covered in Adventure Environments.
- **Ch 7**: treasure and rewards pacing should track the Adventuring Day's encounter cadence.
- **Ch 8**: "Table Rules" and running combat expand on applying the difficulty math live at the table.
- **Appendix B**: Monster Lists by CR is the lookup table for building encounters on an XP budget.
