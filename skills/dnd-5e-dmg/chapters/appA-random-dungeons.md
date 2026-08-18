# Appendix A: Random Dungeons

## Core Idea
A complete dungeon can be procedurally generated in two passes — first roll the physical layout (starting area → passages → doors → chambers → stairs, iteratively extending until you hit map limits), then separately "stock" that layout with purpose, contents, monsters, hazards, traps, and dressing.

## Frameworks Introduced
- **Layout generation pipeline** (roll iteratively, extending every open passage/door until it terminates in a chamber, dead end, or map edge):
  1. **Starting Area** (d10) — a room or intersection configuration; pick one exit as the dungeon's main entrance.
  2. **Passages** — roll on the Passage table (d20) repeatedly per open corridor to extend it (straight runs, turns, side passages, dead ends, or termination in a chamber/stairs); roll Passage Width (d12 if branching from a passage, d20 if leaving a chamber — must be ≥5 ft. narrower than the chamber's longest dimension).
  3. **Doors** — whenever a result indicates a door, roll Door Type (wood/stone/iron/portcullis/secret, each possibly barred or locked) then Beyond a Door (passage, T-intersection, chamber, stairs, or a false door with a trap).
  4. **Chambers** — roll size/shape (d20), then Chamber Exits (count varies by Normal vs. Large chamber), then Exit Location (relative to the entrance) and Exit Type (door vs. 10-ft. corridor) per exit.
  5. **Stairs** — d20 table covering up/down 1-3 levels, chimneys, shafts/elevators, or dead ends; use consistent inter-level spacing (30 ft. is the suggested default).
  6. **Connecting Areas** — after the map is drawn, optionally add doors between adjacent-but-unconnected chambers/passages to open alternate routes, and align vertical features (stairs, shafts) across levels.
  - Constrain sprawl deliberately: cap it to the graph paper's edge (treating overflow as new entrances/unexplored levels) rather than letting the iteration run unbounded.
- **Stocking pipeline** (apply after layout is fixed):
  1. **Chamber Purpose** — use the Dungeon Purpose-specific chamber table matching your Ch 5 Dungeon Purpose choice (Death Trap, Lair, Maze, Mine, Planar Gate, Stronghold, Temple/Shrine, Tomb, Treasure Vault each have their own d20 purpose table), or the catch-all General Dungeon Chambers table.
  2. **Chamber Contents** (d100) — monster (dominant inhabitant / pet-ally / random creature, each with an optional treasure add-on) · dungeon hazard · obstacle · trap (optionally guarding treasure) · trick · empty room (optionally with hazard or treasure).
  3. **Monster Motivation** (d20) — gives placed monsters a goal (sanctuary, conquest, item-seeking, rivalry, hiding, recovering from battle, avoiding danger, wealth-seeking) so encounters aren't automatically "see party, attack."
  4. **Random Dungeon Hazards / Obstacles / Traps / Tricks** — supplementary d20/d100 tables for filling in the Contents roll's specifics (see Reference Tables).
  - **Random rolls will produce incongruous results** (a huge room stocked as storage next to a tiny "temple") — the book explicitly sanctions overriding rolls for a handful of key rooms rather than accepting every result literally.

## Key Concepts
- **Trap generation shortcut**: roll Trap Trigger (d6: stepped on / moved through / touched / opened / looked at / moved) + Trap Effects (d100 flavor: magic missiles, collapsing ceiling, poison gas, glyph of warding, rolling statue, etc.) + Trap Damage Severity (d6: 1-2 Setback, 3-5 Dangerous, 6 Deadly) — then look up actual damage dice on Ch 5/Ch 8's shared Damage Severity by Level table.
- **Obstacle vs. hazard vs. trap vs. trick** — obstacles block progress without necessarily damaging (chasms, cave-ins, flooding, walls of force/fire); hazards are the Ch 5 environmental dangers (molds, slimes, webs); traps are triggered damage/effect devices; tricks are non-lethal "gotcha" set pieces (illusions, reversed levers, false treasure) meant to surprise rather than harm.
- **Dungeon Dressing** — supplementary flavor tables (furnishings, religious articles, mage's furnishings, personal items, container contents, books/scrolls/tomes) for filling empty rooms with texture even when the Contents roll says "empty room."

## Mental Models
- Treat the generator as **two decoupled passes** — layout first (pure geometry), stocking second (purpose/contents/danger) — so you can always hand-author one pass and randomize the other.
- A "dominant inhabitant" controls a chamber; "random creatures" are transient scavengers — this distinction (also used in Ch 3's random encounter design) keeps a stocked dungeon feeling like a lived-in ecology instead of a loot pinata.
- Use the **purpose-specific chamber tables** (keyed to Ch 5's Dungeon Purpose) rather than the generic table whenever the dungeon has a defined purpose — a Tomb's chamber table will naturally produce burial-appropriate rooms a generic roll wouldn't.

## Anti-patterns
- **Letting the passage/chamber iteration run unbounded.** Always set a size limit (graph paper edge, a target chamber count) before starting — the tables have no natural stopping condition on their own.
- **Accepting every random Contents/Purpose result literally when it breaks internal logic.** The book explicitly endorses overriding a handful of key rooms rather than forcing sense onto an absurd roll (tiny temple next to a huge storage closet).
- **Stocking every room with a monster or trap.** The Contents table itself weights toward variety (hazards, obstacles, tricks, empty rooms) — an all-combat dungeon isn't what the generator is built to produce.

## Reference Tables

**Generation roll chain** (in order): Starting Area (d10) → Passage (d20, repeat per corridor) → Passage Width (d12/d20) → Door Type (d20) → Beyond a Door (d20) → Chamber size (d20) → Chamber Exits (d20, Normal/Large) → Exit Location (d20) → Exit Type (d20) → Stairs (d20, as needed) → Chamber Purpose (purpose-specific or general d20) → Chamber Contents (d100) → [Monster Motivation d20 / Hazard d20 / Obstacle d20 / Trap: Trigger d6 + Effect d100 + Severity d6 / Trick tables, as indicated].

**Dungeon Chamber Contents** (d100 summary)
| Roll | Contents |
|---|---|
| 01-15 | Dominant-inhabitant monster (± treasure) |
| 16-33 | Pet/allied creature (± guarding treasure) |
| 34-50 | Random creature (± treasure) |
| 51-58 | Dungeon hazard + incidental treasure |
| 59-63 | Obstacle |
| 64-76 | Trap (± guarding treasure) |
| 77-80 | Trick |
| 81-00 | Empty room (± hazard or treasure) |

**Monster Motivation** (d20): find sanctuary · conquer the dungeon · seek an item · slay a rival · hide from enemies · recover from a battle · avoid danger · seek wealth.

**Trap generation**: Trigger (d6: stepped on / moved through / touched / opened / looked at / moved) + Effect (d100 flavor, e.g. magic missiles, collapsing ceiling, poison gas vent, glyph of warding, disintegrate on touch, rolling statue) + Damage Severity (d6: 1-2 Setback, 3-5 Dangerous, 6 Deadly — cross-reference Ch 5/Ch 8's Damage Severity by Level table for actual dice).

**Random Obstacles** (d20 sample): antilife aura (blocks healing) · battering winds (half speed, ranged disadvantage) · blade barrier · cave-in · chasm (1d4×10 ft wide, 2d6×10 ft deep) · flooding · lava flow · poisonous gas (1d6/minute) · reverse gravity · wall of fire/force.

## Worked Example
Generating a small Tomb dungeon: roll Starting Area → "9, T intersection, 10 ft wide." Roll Passage → "15-19, Chamber" → roll Chamber size → "3-4, Square 30×30" → Chamber Exits (Normal) → "2" → two Exit Locations/Types generate one door and one corridor. For the chamber's purpose, consult the Dungeon: Tomb table (keyed to Ch 5's Purpose choice) instead of the general table, landing on a burial chamber result. Roll Chamber Contents → "64-76, Trap protecting treasure" → Trap Trigger "4, Opened" (a sarcophagus lid) + Effect "20-23, coated with contact poison" + Severity "3-5, Dangerous" → cross-referencing the party's level on the shared Damage Severity table gives the actual damage dice. This two-pass approach (geometry, then purpose-aware stocking) produces a coherent tomb room instead of a generic "trap in a box."

## Key Takeaways
1. Generate layout and stocking as two separate passes — geometry first, purpose/contents second.
2. Always cap the iterative passage/chamber generation at a predetermined size limit before starting.
3. Use the Dungeon Purpose-specific chamber tables (Ch 5) instead of the generic table whenever the dungeon has a defined purpose — it produces thematically coherent rooms for free.
4. Give placed monsters a Motivation, not just a stat block, so encounters can be more than "spot party, attack."
5. Override incongruous random results for key rooms rather than forcing sense onto them.
6. Traps generate from three independent rolls (Trigger, Effect, Severity) that funnel into the same Damage Severity by Level table used everywhere else in the book.

## Connects To
- **Ch 3**: encounter difficulty math applies to any monster placed via the Chamber Contents roll.
- **Ch 5**: Dungeon Purpose, hazards, and the Damage Severity table are all reused directly by this appendix's generation tables.
- **Ch 7**: treasure placement indicated by Chamber Contents rolls uses Treasure's hoard/individual tables.
- **Ch 8**: trap damage severity resolves through the same shared Damage Severity by Level table.
- **Appendix B**: Monster Lists by CR is the natural companion when populating a dominant-inhabitant or random-creature roll.
