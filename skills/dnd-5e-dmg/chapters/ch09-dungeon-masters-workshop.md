# Chapter 9: Dungeon Master's Workshop

## Core Idea
Everything in D&D — monsters, spells, magic items, races, classes, backgrounds — can be homebrewed via the same method: start from an existing example, change the smallest number of things needed for your concept, and use the chapter's power-scaling tables to keep the result balanced.

## Frameworks Introduced
- **Monster creation, two depths**: (1) **Quick Monster Stats** — pick an expected CR, pull AC/HP/attack bonus/damage-per-round/save DC straight off the Monster Statistics by Challenge Rating table (Reference Tables), adjust to taste, then recompute a *final* CR by averaging a defensive CR (from HP, adjusted ±1 per 2 points AC deviates from that CR's expected AC) and an offensive CR (from damage/round, adjusted ±1 per 2 points attack bonus/save DC deviates) — round the average to the nearest CR. (2) **Full Stat Block** — a 20-step sequence (Name → Size → Type → Alignment → Ability Scores → Expected CR → AC → HP → Vulnerabilities/Resistances/Immunities → Attack Bonuses → Damage → Save DCs → Special Traits/Actions/Reactions → Speed → Saving Throw Bonuses → Final CR → Skill Bonuses → Condition Immunities → Senses → Languages), used when you want a Monster-Manual-quality bespoke stat block rather than a fast approximation.
  - **Cheapest customization tier, before either of the above**: reskin an existing stat block (rename it, swap language/alignment/senses — zero CR impact), swap a weapon (remember 2-handed vs 1-handed shield/AC tradeoffs), or bolt on one special trait borrowed from another monster. Changing offense/defense numbers is the only thing that can shift CR.
- **Spell Damage by level** (Reference Tables) — a fixed damage curve for single-target vs. multi-target damage spells at each spell level, assuming half damage on a successful save; **bump damage +25% if the spell doesn't allow a half-damage save**. The same table doubles as the healing-spell-amount guide (cantrips shouldn't heal at all).
- **Magic Item Power by Rarity** (Reference Tables) — caps the max spell level an item can grant (once/day-style) and the max static bonus (+1 to +4) by rarity, so a homebrew item's power stays in line with its intended tier.
- **Attunement rule-of-thumb for new items**: require attunement if (a) passing the item around the party for its lasting benefit would be disruptive, or (b) it grants a bonus type other items also grant (prevents bonus-stacking via item hoarding).
- **Creating a Background, 5 steps**: (1) root it in a specific faction/organization/trade/person/event/location in your world (not a generic "merchant"), (2) suggest 2-3 entries each for personality traits/ideals/bonds/flaws tables, (3) assign 2 skill + 2 tool proficiencies (tool-for-language swaps allowed 1-for-1), (4) include starting equipment (a money package + background-flavored unique items), (5) settle on a background feature that opens roleplaying/plot doors rather than granting a raw mechanical bonus (the sage's Researcher feature is the model: it redirects failure into a new lead, not an automatic success).
- **Creating a Race/Subrace**: start from the *story* (why does the campaign need this race playable? culture, conflicts, relationship to other races) before touching mechanics; benchmark new traits against existing races so the new one is neither strictly worse (unpopular) nor strictly better (power-crept) than published options.
- **Modifying a Class**: four independent levers — changing proficiencies, changing spell lists, restricting class access (e.g. requiring a specific origin/order), substituting class features (swap one archetype feature for a reflavored equivalent) — each usable alone or combined.

## Key Concepts
- **Honor score** (optional 7th ability) — for codes-of-conduct-driven campaigns (samurai/knightly orders); raised/lowered by ±1 at the DM's discretion based on adventure conduct, never via normal ability score increases; monsters without it default to Charisma.
- **Sanity score** (optional 7th ability) — for cosmic-horror campaigns; failed Sanity saves trigger short/long/indefinite madness (Ch 8) and long-term/indefinite madness permanently costs 1 Sanity (restorable via *greater restoration*, or regained via leveling). Monsters without it default to Wisdom.
- **Rest variant dial**: Standard (short 1hr/long 8hr) → **Epic Heroism** (short 5min/long 1hr — combat becomes routine, compensate with harder encounters and consider halving restored spell slots on a short long-rest) → **Gritty Realism** (short 8hr/long 7 days — forces careful risk-judgment, pushes play toward intrigue/politics over back-to-back combat). Pick the tier that matches the campaign's intended pace, not just flavor.
- **Healing variants**: Healer's Kit Dependency (no Hit Dice spending after a short rest without expending a kit use) · Healing Surges (spend Hit Dice as an action mid-combat for parties light on healing magic) · Slow Natural Healing (long rests no longer auto-restore HP — Hit Dice spending required even after a long rest) — each independently dials survivability up or down.
- **Fear vs. Horror** — Fear = WIS save vs. an insurmountable threat, failure = frightened 1 minute (save each turn to end). Horror = CHA save vs. something reality-breaking/revolting, failure = short- or long-term madness (a strictly heavier consequence than Fear).

## Mental Models
- Default to the **cheapest edit that achieves the concept**: reskin > swap a weapon > add one trait > Quick Monster Stats > full stat block, in that order of effort. Most homebrew needs don't require the full 20-step process.
- Treat CR as **two independent axes (defensive, offensive) averaged**, not a single number you eyeball — this is the same logic as Ch 3's encounter math, applied to a single creature's design instead of an encounter's difficulty.
- A background feature is well-designed when it **generates adventure hooks**, not when it grants a check bonus — the acolyte-of-Candlekeep example (free library access, ties to a specific faction's friends/enemies) is the template: mechanical restraint, narrative generativity.

## Anti-patterns
- **Adding a spell so good a caster would always prepare it.** The chapter flags spell over-power exactly this way — if there's no situational tradeoff, the spell is probably underpriced for its level.
- **Designing a class feature/race trait/spell in isolation from its class's identity.** Explicitly called out: giving wizards healing spells "steps on the cleric's turf" — new options should respect existing class/race boundaries unless the campaign is deliberately blurring them.
- **Skipping the story step when creating a race or background.** Jumping straight to mechanics produces flavorless, forgettable options; the chapter insists on the "why does my campaign need this" question first.
- **Granting background features as raw mechanical bonuses** (flat check/attack bonuses) — this cheapens the roleplaying purpose of backgrounds and is explicitly discouraged.
- **Recomputing CR only for one axis.** A monster buffed only in HP without checking whether its damage output still matches will drift out of its intended difficulty band — always average both defensive and offensive CR.

## Reference Tables

**Monster Statistics by Challenge Rating** (selected rows)
| CR | Prof. Bonus | AC | HP | Attack Bonus | Dmg/Round | Save DC |
|---|---|---|---|---|---|---|
| 0 | +2 | ≤13 | 1-6 | ≤+3 | 0-1 | ≤13 |
| 1 | +2 | 13 | 71-85 | +3 | 9-14 | 13 |
| 5 | +3 | 15 | 131-145 | +6 | 33-38 | 15 |
| 10 | +4 | 17 | 206-220 | +7 | 63-68 | 16 |
| 15 | +5 | 18 | 281-295 | +8 | 93-98 | 18 |
| 20 | +6 | 19 | 356-400 | +10 | 123-140 | 19 |
| 25 | +8 | 19 | 581-625 | +12 | 213-230 | 21 |
| 30 | +9 | 19 | 806-850 | +14 | 303-320 | 23 |
*(full table runs every CR 0-30; use it both to design and to sanity-check a homebrew monster's numbers.)*

**Experience Points by Challenge Rating** (selected)
| CR | XP | CR | XP |
|---|---|---|---|
| 0 | 0 or 10 | 15 | 13,000 |
| 1/8 | 25 | 17 | 18,000 |
| 1 | 200 | 20 | 25,000 |
| 5 | 1,800 | 25 | 75,000 |
| 10 | 5,900 | 30 | 155,000 |

**Spell Damage by Level**
| Spell Level | One Target | Multiple Targets |
|---|---|---|
| Cantrip | 1d10 | 1d6 |
| 1st | 2d10 | 2d6 |
| 3rd | 5d10 | 6d6 |
| 5th | 8d10 | 8d6 |
| 9th | 15d10 | 14d6 |
*(assumes half damage on a successful save; +25% damage if no half-damage-on-save clause; also used to size healing-spell HP restored.)*

**Magic Item Power by Rarity**
| Rarity | Max Spell Level (limited-use property) | Max Static Bonus |
|---|---|---|
| Common | 1st | — |
| Uncommon | 3rd | +1 |
| Rare | 6th | +2 |
| Very rare | 8th | +3 |
| Legendary | 9th | +4 |

**Rest variant comparison**
| Variant | Short Rest | Long Rest | Effect |
|---|---|---|---|
| Standard | 1 hour | 8 hours | Baseline heroic pace |
| Epic Heroism | 5 minutes | 1 hour | Combat becomes routine; compensate with harder fights, consider half spell-slot recovery |
| Gritty Realism | 8 hours | 7 days | Forces cautious play; suits intrigue/politics-heavy campaigns |

## Worked Example
Homebrewing a CR 6 "elite guard captain" NPC using Quick Monster Stats: Step 1, expected CR 6. Step 2, pull baseline from the table — AC 15, HP 146-160, attack bonus +6, damage/round 39-44, save DC 15. Step 3, adjust for concept: give it AC 17 (heavily armored) and HP 150 (mid-band). Step 4, recompute final CR — HP 150 still reads as CR 6 defensively, but AC 17 is 2 points above CR 6's expected AC 15, bumping defensive CR to 7; damage/round 40 stays CR 6 offensively with attack bonus +6 matching exactly. Average (7 defensive + 6 offensive) = 6.5, rounds to **CR 7** — the AC buff alone was enough to shift the final rating up a full point, exactly the kind of adjustment the framework exists to catch.

## Key Takeaways
1. Reach for the cheapest edit first: reskin → weapon swap → added trait → Quick Monster Stats → full 20-step stat block.
2. CR is always the average of independently-computed defensive (HP/AC) and offensive (damage/attack bonus or save DC) ratings — never eyeball a single combined number.
3. Use the Spell Damage table (with the +25% no-save-halving adjustment) for any new damage or healing spell.
4. Cap new magic items' power to their rarity's max spell level / max static bonus, and require attunement whenever passing an item around would be disruptive or it stacks with a common bonus type.
5. Ground new backgrounds/races in your world's story before touching mechanics, and give background features that generate adventure hooks, not flat bonuses.
6. Pick a rest-pacing variant (Standard/Epic Heroism/Gritty Realism) deliberately to match your campaign's intended tempo.
7. Honor and Sanity are opt-in 7th ability scores for genre-specific campaigns (code-of-conduct and cosmic-horror respectively) — don't add them unless the campaign's premise calls for them.

## Connects To
- **Ch 3**: encounter-difficulty math is the consumer of any monster built here — a homebrewed monster's CR feeds directly into XP-threshold calculations.
- **Ch 4**: NPCs-with-classes-and-levels guidance here extends Ch 4's NPC statistics options.
- **Ch 7**: magic item and artifact creation tools here extend Treasure's rarity/attunement framework to fully custom items.
- **Ch 8**: madness effects (Fear/Horror, Sanity loss) are resolved using Running the Game's madness tables.
- **Appendix B**: Monster Lists by CR is the natural reference point when placing a newly homebrewed monster into an encounter.
