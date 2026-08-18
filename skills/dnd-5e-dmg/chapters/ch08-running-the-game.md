# Chapter 8: Running the Game

## Core Idea
Nearly every on-the-fly ruling a DM makes — a DC, an NPC's reaction, improvised damage, whether a creature notices another — reduces to a small set of shared frameworks (Typical DCs, Advantage/Disadvantage circumstances, the 4-step Social Interaction resolution, the Damage Severity table) that you should internalize once and reuse everywhere.

## Frameworks Introduced
- **Typical DCs**: Very Easy 5 · Easy 10 · Moderate 15 · Hard 20 · Very Hard 25 · Nearly Impossible 30. Rule of thumb: if you only ever use 10/15/20, the game runs fine. A DC 5 task shouldn't even require a roll for a capable character. DC 25 is very hard for low-level characters but reasonable past 10th; DC 30 needs a near-max roll even from a 20th-level specialist.
- **Advantage/disadvantage grant criteria**: grant advantage when circumstances unrelated to inherent capability provide an edge, the environment helps, a player shows exceptional creativity, or prior actions improved the odds. Impose disadvantage under the mirrored conditions. **They always cancel in pairs** — never stack multiple advantages or multiple disadvantages, and don't bother enumerating every small factor once one of each side is present.
- **Social Interaction resolution (4 steps)**: (1) set Starting Attitude (Friendly/Indifferent/Hostile), (2) play out the Conversation — attitude can shift at most **one step** per interaction, temporarily or permanently, and touching a known ideal/bond/flaw is how it shifts (a Wisdom (Insight) check can reveal one, but failing by 10+ risks learning a *false* or inverted trait), (3) call for a Charisma check when the ask lands — DC required depends on current attitude and the size of the risk/sacrifice being requested (see Reference Tables), with helpful bystanders granting advantage and unhelpful ones imposing disadvantage, (4) decide whether repeating is fruitless or risks shifting attitude toward hostile.
- **Resolution flourishes**: Success at a Cost (fail by 1-2 → succeed but with a complication instead of an outright fail), Degrees of Failure (fail by 5+ → worse consequence than a narrow miss), Critical Success/Failure on ability checks (natural 20/1 — optional extra flavor, not automatic in 5e rules as written for non-attack rolls).
- **Improvising Damage / Damage Severity by Level** — the single shared severity table reused everywhere in the book (traps, hazards, improvised damage): pick a die count (1d10 setback-scale up to 24d10 deity-scale) matched to a Setback/Dangerous/Deadly tier at the party's level band. This is the same table introduced in Ch 5 for traps — one framework, one lookup, used for every "how much damage should this do" question in the game.
- **Chases**: pursuer(s) + quarry roll initiative; everyone wants to Dash every round. Free Dash actions = 3 + Constitution modifier; each Dash beyond that needs a DC 10 Constitution check or 1 exhaustion level (5 levels = speed 0, drop out). Each round after actions resolve, the quarry rolls Dexterity (Stealth) vs. pursuers' passive Perception to escape (auto-fail if never out of the lead pursuer's sight); Escape Factors (things to hide behind, crowd noise, a ranger/Survival-proficient pursuer) grant/impose advantage/disadvantage. Random Complications (d20 per participant each round, affecting the *next* participant in order) add chaos; spend Inspiration to negate one.
- **XP awarding models** (pick one per campaign, or mix): standard combat-defeat XP split evenly among participants (including helping NPCs, which dilutes PC shares) · Noncombat Challenge XP (treat a risky non-combat challenge as a combat encounter of equivalent difficulty, Ch 3 math) · **Milestones** (award XP for major/minor story beats, treated as hard/easy encounters respectively; can also grant free short rests, Hit Die recovery, or item-charge recovery instead of/alongside XP) · **Level Advancement without XP** (session-based: 2nd level after session 1, 3rd after another, 4th after two more, then ~2-3 sessions/level thereafter; or story-based: award levels at narrative goals).

## Key Concepts
- **Automatic success variant** — DC ≤ (ability score − 5) auto-succeeds; DC ≤10 auto-succeeds with proficiency (≤15 at 11th+ level). Trades unpredictability for predictability — use cautiously since it rewards always routing checks through the highest stat.
- **Inspiration** — one-at-a-time resource granting advantage on one check/attack/save; award roughly once per session per character as a baseline. Four award philosophies: Roleplaying (reward acting on trait/ideal/bond/flaw), Heroism (reward risk-taking; consider letting it be spent *after* the roll for action-movie campaigns), Reward for Victory (everyone gets it after beating a major challenge, for DMs who prefer dice-driven impartiality), Genre Emulation (reward leaning into shared genre-flaw conventions agreed on up front).
- **Milestone bonus rewards** beyond XP: a free short rest, Hit Die recovery, or recovering expended magic item charges at a milestone.
- **Madness** — Short-term (1d10 minutes, mostly incapacitating effects), Long-term (1d10×10 hours, compulsions/phobias/amnesia-flavored), Indefinite (a permanent flaw until cured). Resisted with a WIS or CHA save (or Sanity save, if using that optional score). Curing: *calm emotions* suppresses; *lesser restoration* cures short/long-term; *greater restoration*+ needed for indefinite.
- **Absent characters** — default: no session, no XP (creates natural level gaps, which the book says is fine up to 2-3 levels); optional variant: absent PCs get the same XP as the party to keep the group level-synced.

## Mental Models
- Treat every "how hard is this" question as a **Typical DCs lookup**, not a bespoke judgment call — consistency here is what makes player planning meaningful.
- Advantage/disadvantage is a **binary toggle, not a stacking resource** — the moment one of each exists, stop counting.
- The Social Interaction 4-step structure should stay **invisible at the table** — it's a DM-side scaffold for consistency, not a procedure to narrate to players.
- Improvised damage and hazard/trap damage are **the same lookup** — memorize the Damage Severity table once (Setback/Dangerous/Deadly × level band) and stop inventing bespoke numbers per situation.

## Anti-patterns
- **Rolling dice for very-easy (DC 5) tasks.** If a capable character would obviously succeed, skip the roll — rolling anyway just introduces bad-luck absurdity (the DC-15-door example with a high-STR fighter flailing).
- **Letting the auto-success variant swallow risk entirely.** Once an ability score hits 20, many checks become guaranteed — either accept the predictability or set higher DCs (which then leans harder on luck, the opposite problem).
- **Shifting a creature's attitude more than one step per interaction.** The framework explicitly caps this — hostile-to-friendly in one conversation isn't supported.
- **Telegraphing inspiration awards before the action, by default.** The book recommends starting with after-the-fact awards, especially for new tables, to avoid the DM feeling like they're steering player choices.
- **Forgetting that chase complications hit the next participant in initiative, not the roller.** Misapplying this breaks the intended chaos/fairness of the subsystem.

## Reference Tables

**Typical DCs**
| Task | DC |
|---|---|
| Very easy | 5 |
| Easy | 10 |
| Moderate | 15 |
| Hard | 20 |
| Very hard | 25 |
| Nearly impossible | 30 |

**Conversation Reaction — DC needed by starting attitude**
| Attitude | DC 0 | DC 10 | DC 20 |
|---|---|---|---|
| Friendly | Helps without risk (no check needed) | Accepts minor risk/sacrifice | Accepts significant risk/sacrifice |
| Indifferent | No help, no harm | Helps if no risk involved | Accepts minor risk/sacrifice |
| Hostile | Actively opposes | No help, no harm | Helps if no risk involved |

**Damage Severity by Level** (shared with Ch 5 — memorize once)
| Level | Setback | Dangerous | Deadly |
|---|---|---|---|
| 1st-4th | 1d10 | 2d10 | 4d10 |
| 5th-10th | 2d10 | 4d10 | 10d10 |
| 11th-16th | 4d10 | 10d10 | 18d10 |
| 17th-20th | 10d10 | 18d10 | 24d10 |

**Map Travel Pace**
| Map Scale | Slow | Normal | Fast |
|---|---|---|---|
| Dungeon (1 sq=10ft) | 20 sq/min | 30 sq/min | 40 sq/min |
| City (1 sq=100ft) | 2 sq/min | 3 sq/min | 4 sq/min |
| Province (1 hex=1mi) | 2 hex/hr, 18/day | 3 hex/hr, 24/day | 4 hex/hr, 30/day |
| Kingdom (1 hex=6mi) | 1 hex/3hr, 3/day | 1 hex/2hr, 4/day | 1 hex/1.5hr, 5/day |

**Chase Dash limit**: free Dashes = 3 + CON modifier; each extra Dash = DC 10 CON check or +1 exhaustion; 5 exhaustion levels = speed 0, drops out.

**Escape Factors** (advantage/disadvantage on the quarry's Stealth check): many things to hide behind → advantage; crowded/noisy area → advantage; few things to hide behind → disadvantage; uncrowded/quiet area → disadvantage; lead pursuer is a ranger or Survival-proficient → disadvantage (for the quarry).

**Madness durations**: Short-term = 1d10 minutes · Long-term = 1d10×10 hours · Indefinite = until cured (calm emotions suppresses; lesser restoration cures short/long; greater restoration+ cures indefinite).

**XP/leveling model comparison**
| Model | Best for |
|---|---|
| Standard combat XP | Combat-heavy, crunchy campaigns |
| Noncombat challenge XP | Rewarding risky social/exploration play |
| Milestones | Story-paced, avoids bookkeeping mid-arc |
| Session-based advancement | Low-combat or combat-heavy games where XP tracking is tedious |
| Story-based advancement | Narrative campaigns driven by DM pacing, not math |

## Worked Example
Resolving a tense negotiation with a hostile local lord using the 4-step framework: Starting Attitude = Hostile. During Conversation, the party's bard makes a Wisdom (Insight) check (DC 15, succeeds) to learn the lord's Bond is "protective of his younger sister" — they use this to appeal to protecting his family's future, shifting him from Hostile to Indifferent (the one-step cap). They then call for the Charisma check: since he's now Indifferent and they're asking him to commit troops (a real risk), they need DC 20 on the Conversation Reaction table. The bard rolls Persuasion with advantage (another party member's supportive comment counted as aid) and succeeds — the lord commits troops despite the risk. A second ask in the same conversation (asking for gold too) risks shifting him back toward hostile, so the DM rules it fruitless for this session.

## Key Takeaways
1. Use the fixed Typical DC ladder (5/10/15/20/25/30) instead of improvising DCs from scratch each time.
2. Advantage/disadvantage always cancel in pairs — treat it as a binary toggle, never a stack.
3. Run social interactions through the 4-step Attitude → Conversation → Charisma Check → Repeat? structure, but keep the mechanics invisible to players.
4. The Damage Severity by Level table (Setback/Dangerous/Deadly × level band) is the single shared answer to "how much damage should this improvised/environmental effect deal" — same table as Ch 5's traps.
5. Chases run on Dash-limited action economy plus a Stealth-vs-passive-Perception escape check each round, with Escape Factors and random Complications for texture.
6. Pick one XP/advancement model deliberately (combat XP, noncombat XP, milestones, or session/story-based) rather than mixing inconsistently.
7. Madness severity (short/long-term/indefinite) should match how horror-forward the campaign is — most campaigns need it rarely, if ever.

## Connects To
- **Ch 3**: encounter-difficulty math is reused directly for Noncombat Challenge XP and Milestone-as-encounter-difficulty framing.
- **Ch 4**: an NPC's Ideal/Bond/Flaw (Ch 4's Ten Sentences) is exactly what the Social Interaction framework's attitude-shift mechanic operates on.
- **Ch 5**: the Damage Severity table and DC-setting guidance here are the general form of what Ch 5 applies specifically to traps/hazards.
- **Ch 7**: cursed items and certain artifact properties can inflict the madness effects detailed here.
- **Ch 9**: Sanity score (if used) replaces WIS/CHA saves for resisting madness-inducing effects.
