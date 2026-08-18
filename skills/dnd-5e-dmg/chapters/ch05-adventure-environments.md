# Chapter 5: Adventure Environments

## Core Idea
Dungeons, wilderness, and settlements each have their own build procedure and hazard toolkit — and every trap or environmental hazard, regardless of flavor, reduces to the same handful of reusable mechanics (detect DC, save DC / attack bonus tier, and a damage-by-level table).

## Frameworks Introduced
- **Dungeon build stack** (layer these, in any order): Creator (who built it — beholder, dwarves, a lich, "no creator/natural cavern," etc.) → Purpose (Death Trap, Lair, Maze, Mine, Planar Gate, Stronghold, Temple/Shrine, Tomb, Treasure Vault) → History (what happened to the creators — abandoned, conquered, destroyed by plague/disaster/internal conflict, cursed, or "original creator still in control") → Inhabitants/Factions (who lives there now, and whether multiple factions compete for space — an exploitable seam for the party).
  - Why it matters: Creator shapes physical design (ramps not stairs for a snake-cult; smooth disintegrated walls for a beholder lair); Purpose shapes encounter/trap density; History explains *why* the dungeon is explorable at all instead of still being actively defended at full strength.
- **Trap severity framework** (reusable for any trap or hazard): pick a danger tier — Setback / Dangerous / Deadly — which sets both the Save DC / attack bonus band AND the damage dice, scaled by party level (see Reference Tables). This is the same table Ch 8 uses for adjudicating any DC on the fly.
- **Trap anatomy**: every trap needs a Trigger (pressure plate, tripwire, wrong key, password), a Detection method (passive/active Perception, sometimes Investigation to figure out disarming), and an Effect. **Complex traps** roll initiative and act every round like a monster (e.g. a slow-flooding room) instead of firing once.
- **Wilderness travel granularity**: choose Travel-Montage (narrate days quickly, check in at decision points) or Hour-by-Hour (track exact time/distance) depending on how much the journey itself matters to the current adventure.
- **Becoming Lost**: the party navigator makes a Wisdom (Survival) check (DC by terrain, see Reference Tables) when you call for it; slow pace = +5, fast pace = -5; a map or visible sun/stars = advantage. Fail = travel the wrong direction; retry after 1d6 hours.

## Key Concepts
- **Secret door vs. concealed door** — a secret door is built to blend into the surrounding surface (found via passive/active Perception, opened via Investigation); a concealed door is a normal door hidden by mundane means (tapestry, rug) and needs no check to find once a character looks in the right place — only passive Perception to notice *disturbance* (a moved rug) pointing toward it.
- **Hazard vs. trap** — mechanically treated the same way (Reference Tables' severity/damage framework applies to both); a hazard usually needs no check to notice unless it's disguised as something benign (e.g. mold mistaken for a stain — Nature check to correctly ID it).
- **Complex trap** — a trap that rolls initiative and acts on its own turns, for effects that unfold over multiple rounds rather than firing once.
- **High altitude acclimation** — 10,000+ ft: every hour of travel counts double for endurance purposes; can't acclimate above 20,000 ft unless native to such elevations.

## Mental Models
- Treat **every environmental danger** (trap, hazard, weather extreme) as an instance of the same save-or-suffer template: identify the DC, the save type, and — if damage — the tier from the Damage Severity table. You don't need bespoke math per hazard.
- Use the **Dungeon Faction** idea as a design lever, not just flavor: a dungeon with 2+ competing groups (goblins vs. their mind flayer masters) gives the party a diplomatic/subversive alternative to a straight fight — always worth stocking multi-faction dungeons deliberately.
- Foraging, food/water needs, and navigation DCs exist to make wilderness travel a resource-management minigame *only when the DM wants it to be* — these systems are opt-in texture, not mandatory bookkeeping for every journey.

## Anti-patterns
- **Letting die rolls override obviously clever play.** The chapter is explicit: if lifting a rug plainly reveals a pressure plate, no roll is needed — don't force a check when the fiction already answers the question.
- **Traps or hazards nobody could reasonably detect or that instantly kill with no save.** The whole framework assumes a detect method and a save; skipping either turns a trap into "gotcha" DM fiat, which the source material's own tone argues against (traps should be discoverable, not just felt).
- **Random encounters or hazards untethered to terrain/faction logic.** A Sylvan Forest encounter table (Ch 3) works because every entry has a reason to be there; the same logic applies to dungeon hazards — pick hazards that fit the Creator and Purpose, not a generic grab-bag.

## Reference Tables

**Trap Save DCs and Attack Bonuses (by danger tier)**
| Trap Danger | Save DC | Attack Bonus |
|---|---|---|
| Setback | 10-11 | +3 to +5 |
| Dangerous | 12-15 | +6 to +8 |
| Deadly | 16-20 | +9 to +12 |

**Damage Severity by Level** (dice, cross-referenced with danger tier above)
| Character Level | Setback | Dangerous | Deadly |
|---|---|---|---|
| 1st-4th | 1d10 | 2d10 | 4d10 |
| 5th-10th | 2d10 | 4d10 | 10d10 |
| 11th-16th | 4d10 | 10d10 | 18d10 |
| 17th-20th | 10d10 | 18d10 | 24d10 |
*(This table is shared with Ch 8's general DC-setting guidance — one framework, used everywhere a DM needs to price a save-or-suffer effect.)*

**Wilderness Navigation (Becoming Lost) DC by terrain**
| Terrain | DC |
|---|---|
| Forest, jungle, swamp, mountains, open sea (overcast, no land) | 15 |
| Arctic, desert, hills, open sea (clear skies, no land) | 10 |
| Grassland, meadow, farmland | 5 |

**Environmental hazard quick-reference**
| Hazard | Trigger/Save | Effect |
|---|---|---|
| Extreme cold (≤0°F) | DC 10 CON/hour | 1 exhaustion level on fail (immune: cold resist/immune, cold gear, cold-adapted) |
| Extreme heat (≥100°F) | DC 5+1/hr CON | 1 exhaustion level on fail; disadvantage in medium/heavy armor |
| Strong wind | — | Disadvantage on ranged attacks & hearing Perception; extinguishes flames; forces flying creatures to land |
| Heavy precipitation | — | Lightly obscured; disadvantage on sight/hearing Perception; extinguishes flames |
| Frigid water | DC 10 CON after CON-score minutes | 1 exhaustion level/additional minute |
| Quicksand | Sinks 1d4+1 ft then 1d4 ft/turn | STR check (DC 10+ft sunk) to escape; can't breathe if fully submerged |
| Slippery ice | DC 10 DEX (Acrobatics) | Fall prone |
| Thin ice | Weight > 3d10×10 lb per 10-ft square | Breaks, creatures fall through |
| Razorvine (wall) | DC 10 DEX on contact | 5 (1d10) slashing; wall: AC 11, 25 HP |
| Green slime | DC 10 DEX to avoid drop | 5 (1d10) acid/round until removed; destroyed by sun/cold/fire/radiant/cure disease |
| Brown mold | DC 12 CON within 5 ft | 22 (4d10) cold; expands toward fire, destroyed by cold damage |
| Yellow mold | Touch → DC 15 CON | 11 (2d10) poison + poisoned 1 min (5/turn poison while poisoned) |
| Giant webs | DC 12 DEX first turn in area | Restrained; escape DC 12 STR(Athletics)/DEX(Acrobatics); 10-ft cube: AC 10, 15 HP, vulnerable fire |

**Dungeon Purpose** (d20): Death Trap · Lair · Maze · Mine · Planar Gate · Stronghold · Temple/Shrine · Tomb · Treasure Vault.

**Dungeon History** (d20 sample): Abandoned by creators · Abandoned due to plague · Conquered by invaders · Destroyed by internal conflict/magical catastrophe/natural disaster · Cursed by the gods and shunned · Original creator still in control · Overrun by planar creatures · Site of a great miracle.

## Worked Example
Building a dungeon with the stack: Creator roll → "Kuo-toa" (amphibious, so expect flooded lower levels). Purpose roll → "Temple or Shrine." History roll → "Conquered by invaders" — so the current inhabitants aren't the kuo-toa who built it, but whoever conquered them (say, a sahuagin raiding party, reusing the flooded architecture for their own aquatic worship). This immediately generates a two-faction dungeon (surviving kuo-toa remnants vs. sahuagin conquerors) without extra design work — matching the Dungeon Factions guidance that a multi-group dungeon gives the party a political lever, not just a combat gauntlet. Populate one deadly-tier trap guarding the inner shrine using the framework: Save DC 16-20 range, damage from the 11th-16th-level Deadly row (18d10) if the party is that level.

## Key Takeaways
1. Layer Creator → Purpose → History → Inhabitants/Factions to generate a coherent dungeon fast, rather than placing rooms first and rationalizing later.
2. Every trap/hazard reduces to trigger + detection + the shared Save-DC/damage-severity-by-level table — learn that table once, reuse it everywhere.
3. Complex traps (rolling initiative) are the right tool when a hazard should escalate over several rounds instead of firing once.
4. Multi-faction dungeons give players a non-combat lever — deliberately stock more than one competing group when it fits the Creator/History.
5. Wilderness survival subsystems (foraging, navigation, weather, altitude) are opt-in texture — use only the pieces that serve the current adventure's tension.
6. Never force a roll when the fiction already makes the answer obvious (an inspected, lifted rug reveals its own trapdoor).

## Connects To
- **Ch 3**: encounter-difficulty math applies to any dungeon/wilderness combat encounter built here.
- **Ch 6**: strongholds built by high-level characters use similar location-design logic in reverse (players as creators).
- **Ch 8**: the DC-setting guidance and Damage Severity table are the general-purpose version of what this chapter applies specifically to traps/hazards.
- **Ch 9**: "Creating a Trap" in the DM's Workshop extends this chapter's trap framework to fully custom trap design.
- **Appendix A**: Random Dungeons operationalizes this chapter's Dungeon build stack into a fully proceduralized generator.
