# Chapter 7: Treasure

## Core Idea
Treasure isn't just loot placement — it's a rarity-and-attunement economy (5 rarity tiers gated to character level, max 3 attuned items per creature) layered on top of a fully proceduralized random-generation system (CR-keyed treasure hoard tables → lettered magic item tables A-I) that a DM can use as-is or override entirely for story reasons.

## Frameworks Introduced
- **Magic Item Rarity ↔ Character Level ↔ Value** (see Reference Tables): rarity is a rough power/level gate and a price-setting tool simultaneously — but the book explicitly says rarity "shouldn't get in the way of your campaign's story" (a 1st-level character finding a ring of invisibility is fine if the story wants it).
- **Attunement**: a bond a creature forms with certain items via a short rest of focused activity (can't be the same short rest used to *identify* the item). Hard caps: **attuned to at most 3 items at once**; can't attune to more than one copy of the same item; attunement ends automatically if prerequisites stop being met, the item is 100+ feet away for 24+ hours, the creature dies, or another creature attunes to it. Items with a class/spellcaster prerequisite gate who can attune at all.
- **Treasure generation pipeline**: (1) roll on an Individual Treasure table (CR 0-4 / 5-10 / 11-16 / 17+) for pocket change on a single creature, OR (2) roll on the matching Treasure Hoard table for a lair/group/quest-reward hoard, which yields coins + a chance at gems/art objects + a chance at rolling on one or more lettered Magic Item Tables (A through I, roughly ascending in power — A is mostly common consumables like potion of healing, B mixes uncommon potions/scrolls/wondrous items, higher letters skew toward rarer items). Legendary creatures or hoarders should roll **at least twice** and sum results.
  - Campaign-scale guideline: over a full campaign, a party finds roughly 7 rolls on the CR 0-4 hoard table, 18 on CR 5-10, 12 on CR 11-16, and 8 on CR 17+.
- **Cursed items**: identification methods (including *identify*) typically fail to reveal a curse — it should surprise the player when it manifests. Attunement to a cursed item can't be voluntarily ended without first breaking the curse (e.g. *remove curse*).
- **Sentient item creation**: give the item INT/WIS/CHA (roll 4d6-drop-lowest or choose), a Communication mode (emotion-only / speech / speech+telepathy), Senses (range + darkvision or not), an Alignment, NPC-style Characteristics (Ch 4's ideal/bond/flaw/mannerism toolkit), and optionally a **Special Purpose** (Aligned, Bane, Protector, Crusader, Templar, Destroyer, Glory Seeker, Lore Seeker, Destiny Seeker, Creator Seeker). If the wielder acts against the item's alignment/purpose, it can contest with a Charisma check to suppress properties or attempt to charm/control the wielder (DC 12 + item's CHA mod).
- **Artifact properties system**: an artifact can carry up to **4 minor + 2 major beneficial properties** and **4 minor + 2 major detrimental properties**, each drawn from d100 tables (see Reference Tables) — properties are typically re-rolled/reassigned each time the artifact resurfaces in the world, so the "same" artifact can play differently across campaigns. Every artifact needs a specific, discoverable **destruction method** (melt in its forge of creation, feed to the tarrasque, bathe in a god's blood, shatter with a purpose-built weapon, etc.) — otherwise it's indestructible.

## Key Concepts
- **Individual vs. Treasure Hoard tables** — Individual = one creature's pocket change (or victims' leavings); Hoard = the accumulated wealth of a group, a serious hoarder, or a quest reward. Use the CR of the group's leader (or the party's average level, for a benefactor's gift) to pick the right hoard table.
- **Magic item categories**: armor, potions, rings, rods, scrolls, staffs, wands, weapons, wondrous items — each with its own subset of typical properties (e.g. only weapons/armor take a flat "+1/+2/+3" bonus format).
- **Consumables** (potions, scrolls) — typically valued at **half** the price of a permanent item of the same rarity, and are never sentient.
- **Artifacts as plot devices, not loot** — the book is explicit that artifacts "only appear when you want them to"; recovering one is usually the spine of an adventure or campaign arc, not a hoard-table roll.
- **Epic Boons** — 24 named capstone rewards (Boon of Combat Prowess, Immortality, Truesight, Peerless Aim, etc.) offered in place of further leveling to 20th-level characters, giving continued mechanical growth without more levels.
- **Other Rewards (non-magic-item)** — Supernatural Gifts (Blessings, Charms), Marks of Prestige (letters of recommendation, medals, titles, land grants, special rights/favors), and Strongholds — reputation- and story-based rewards that don't consume a hoard-table roll at all.

## Mental Models
- Treat rarity as a **level-appropriateness heuristic, not a hard rule** — override it freely when the story calls for it (the book's own example: a 1st-level ring of invisibility).
- Think of the lettered Magic Item Tables (A-I) as a **difficulty dial**: higher letters == rarer/more powerful loot, and Treasure Hoard tables mix multiple letters at higher CR bands to blend common utility items with headline rare finds in the same hoard.
- An artifact's detrimental properties exist to make wielding it a **genuine dilemma**, not just a power spike — always pair major benefit with real cost (a body-part-rotting curse, a forced quest, vulnerability to all damage) so players must weigh keeping it against its price.

## Anti-patterns
- **Letting attunement slots go unenforced.** The 3-item cap is a deliberate scarcity mechanic that keeps magic-item power in check — don't let players stack unlimited "requires attunement" items.
- **Revealing a cursed item's curse via identify or short-rest study.** That defeats the intended surprise; curses should surface through use, not detection.
- **Treating artifacts as ordinary hoard loot.** Rolling one on a random table undermines their intended role as campaign-defining plot devices with bespoke recovery arcs and destruction conditions.
- **Handing out magic items purely by treasure-table roll with no narrative logic.** Intelligent monsters use and hide items sensibly (a hobgoblin warlord wields the hoard's magic sword; a jug of alchemy stays stashed) — loot placement should still make in-world sense.

## Reference Tables

**Magic Item Rarity**
| Rarity | Character Level | Value |
|---|---|---|
| Common | 1st+ | 50-100 gp |
| Uncommon | 1st+ | 101-500 gp |
| Rare | 5th+ | 501-5,000 gp |
| Very rare | 11th+ | 5,001-50,000 gp |
| Legendary | 17th+ | 50,001+ gp |

**Treasure by CR band (coin order of magnitude, hoard tables)**
| CR band | Coins (approx.) | Magic item letters typically rolled |
|---|---|---|
| 0-4 | Hundreds of gp | A, B, C, F, G |
| 5-10 | Low thousands of gp | A-H |
| 11-16 | Tens of thousands of gp | A-I |
| 17+ | Tens of thousands+ gp | higher letters weighted more heavily |

**Gemstone value tiers** (by base value, sample stones): 10 gp (azurite, banded agate, hematite, turquoise) · 50 gp (bloodstone, carnelian, moonstone, onyx) · 100 gp (amber, amethyst, garnet, jade, pearl) · 500 gp (alexandrite, aquamarine, black pearl, topaz) · 1,000 gp (black opal, blue sapphire, emerald, star ruby) · 5,000 gp (black sapphire, diamond, jacinth, ruby).

**Art object value tiers** (sample): 25 gp (silver ewer, small gold bracelet) · 250 gp (gold ring w/ bloodstones, bronze crown) · 750 gp (small gold idol, ceremonial electrum dagger) · 2,500 gp (old masterpiece painting, platinum bracelet w/ sapphire) · 7,500 gp (jeweled gold crown, gold cup set with emeralds).

**Sentient item alignment** (d100): weighted toward good/neutral (66% good-or-neutral-good bands) but can land anywhere on the 9-alignment grid.

**Sentient item Special Purpose** (d10): Aligned (opposed-alignment destroyer) · Bane (hunts a creature type) · Protector (defends a race) · Crusader / Templar (opposes/serves a deity's agents) · Destroyer (craves arbitrary combat) · Glory Seeker · Lore Seeker · Destiny Seeker · Creator Seeker.

**Artifact property budget**: up to 4 minor + 2 major beneficial, and up to 4 minor + 2 major detrimental properties, each rolled independently off d100 tables (examples — minor beneficial: skill proficiency, disease immunity, a castable cantrip/1st-3rd level spell; major beneficial: +2 to an ability score, extra weapon damage, a 4th-7th level castable spell, condition immunity; minor detrimental: disadvantage on saves vs. spells/poison, sensory impairment near/far from the item; major detrimental: forced *geas*-like quest, alignment randomized daily, 4d10-8d10 psychic damage on attunement, imprisoned hostile creature with an escape chance).

## Worked Example
Stocking a CR 8 dragon's lair hoard: roll on Treasure Hoard: Challenge 5-10 (dragon's own CR sets the table). Coins land in the thousands of gp; a hoard-table roll indicates 3d6 (10) 500 gp gems plus "Roll 1d4 times on Magic Item Table F" — yielding a mix of uncommon/rare wondrous items. Because dragons are notorious hoarders, roll **twice more** on the table and sum results, per the "legendary creatures accumulate more" guidance, then hand-place one high-value item deliberately (say, a sentient weapon with a Glory Seeker purpose) rather than leaving everything to chance, since a dragon's hoard is exactly the kind of narratively significant cache worth curating on top of the random baseline.

## Key Takeaways
1. Rarity gates power roughly to character level and sets price, but is explicitly a guideline the DM can break for story reasons.
2. Attunement is capped at 3 items — enforce this scarcity to keep magic-item power in check.
3. Use the Individual/Hoard table pipeline (CR-keyed) plus lettered Magic Item Tables A-I as your default loot-generation engine; roll multiple times for legendary hoarders.
4. Cursed items must stay hidden from identification methods — the surprise is the point.
5. Sentient items are NPCs with their own ideal/bond/flaw/alignment/purpose (Ch 4 toolkit) and can resist or punish a misaligned wielder.
6. Artifacts are plot devices, not hoard-table entries — give every one a bespoke recovery arc and a specific, discoverable destruction method.
7. Epic Boons and non-item rewards (Blessings, Charms, titles, land, strongholds) are valid alternatives to magic-item loot, especially at the high end of the level range.

## Connects To
- **Ch 1**: Tiers of Play sets which rarity tiers are appropriate for the party's current level.
- **Ch 3**: encounter/adventuring-day pacing (Ch 3) should inform hoard placement cadence.
- **Ch 4**: sentient-item characterization directly reuses the Ten Sentences / ideal-bond-flaw NPC framework.
- **Ch 6**: crafting, selling, and attuning to magic items during downtime uses this chapter's rarity/value tables.
- **Ch 8**: cursed-item surprises and long-term madness (from certain artifact properties) use Running the Game's madness rules.
- **Ch 9**: DM's Workshop covers designing wholly custom magic items and artifacts beyond this chapter's tables.
