---
name: dnd-5e-dmg
description: "Knowledge base from \"Dungeon Master's Guide\" (D&D 5th Edition, 2014) by Mike Mearls, Jeremy Crawford, et al. (Wizards of the Coast). Use when applying the DMG's frameworks for building D&D campaigns/worlds, designing adventures and encounters, calculating combat difficulty (XP thresholds), placing treasure and magic items, running social interactions and traps, homebrewing monsters/spells/items/races, or referencing any DMG rule, table, or procedure."
license: MIT
metadata:
  version: "1.0.0"
  author: Ariana Maghsoudi
  email: ariana.maghsoudi82@gmail.com
  sources:
    - "Dungeons & Dragons 2024 Dungeon Master's Guide (D&D Core Rulebook)"
---

<!-- argument-hint: [topic, framework name, or chapter number] -->

# Dungeon Master's Guide
**Author**: Mike Mearls, Jeremy Crawford, et al. (Wizards of the Coast) | **Pages**: ~320 | **Chapters**: 9 + 4 appendices | **Generated**: 2026-08-18

## How to Use This Skill

- **Without arguments** — load core frameworks for reference
- **With a topic** — ask about `encounter difficulty`, `treasure`, `NPC creation`, or another indexed topic; I find and read the relevant chapter
- **With chapter** — ask for `ch03` or `appA`; I load that specific file
- **Browse** — ask "what chapters do you have?" to see the full index

When you ask about a topic not covered in Core Frameworks below, I will read the relevant chapter file before answering.

---

## Core Frameworks & Mental Models

**Combat Encounter Difficulty (Ch 3)** — the DMG's single most load-bearing framework. Sum each PC's per-level XP threshold (Easy/Medium/Hard/Deadly) across the party → sum monster XP → multiply by an Encounter Multiplier keyed to monster *count* (×1 solo up to ×4 for 15+) → compare adjusted XP to party thresholds. A full adventuring day budgets ~6-8 medium/hard encounters with ~2 short rests. See `cheatsheet.md` for the exact tables.

**Damage Severity by Level (Ch 5 & Ch 8, one shared table)** — every trap, hazard, and improvised-damage question in the book reduces to the same Setback/Dangerous/Deadly × character-level lookup. Learn it once, reuse everywhere — don't invent bespoke damage numbers per situation.

**Typical DCs (Ch 8)** — Very Easy 5 · Easy 10 · Moderate 15 · Hard 20 · Very Hard 25 · Nearly Impossible 30. Skip rolling for DC 5. If you only ever use 10/15/20, the game runs fine.

**Tiers of Play (Ch 1)** — Levels 1-4 "Local Heroes" / 5-10 "Heroes of the Realm" / 11-16 "Masters of the Realm" / 17-20 "Masters of the World." Use this to calibrate every threat, magic item rarity, and stake to the party's current tier instead of guessing.

**Core Assumptions Inversion (Ch 1)** — a homebrew world starts from 5 defaults (gods oversee the world / world is untamed / world is ancient / conflict shapes history / world is magical). Invert 1-2 deliberately and trace the downstream implications to make a setting distinctive fast.

**World-Shaking Events (Ch 1)** — budget ~3 per campaign (beginning/middle/end). More becomes "false action" and stops landing. Small local-scale events can happen as often as you like.

**Ten Sentences NPC Build (Ch 4)** — one sentence each for Occupation/History, Appearance, Abilities, Talent, Mannerism, Interactions, Useful Knowledge, Ideal, Bond, Flaw/Secret. Reserve for NPCs with narrative weight; one or two traits is enough for background extras. Ideal/Bond/Flaw are mechanically active — a PC who learns one can use it to shift the NPC's attitude in social interaction (Ch 8).

**Villain Objective × Method (Ch 4)** — factor a villain's *why* (Immortality/Influence/Magic/Mayhem/Passion/Power/Revenge/Wealth) independently from their *how* (a large tactics table) to avoid cookie-cutter antagonists.

**Dungeon Build Stack (Ch 5, Appendix A)** — Creator → Purpose → History → current Inhabitants/Factions. Multi-faction dungeons give players a diplomatic/subversive lever, not just a combat gauntlet.

**Social Interaction 4-Step (Ch 8)** — set Starting Attitude (Friendly/Indifferent/Hostile) → play the Conversation (attitude shifts at most 1 step, via a discovered Ideal/Bond/Flaw) → Charisma check at a DC keyed to attitude + ask size → decide if repeating is fruitful. Keep the scaffold invisible to players.

**Magic Item Rarity ↔ Level ↔ Attunement (Ch 7)** — 5 rarity tiers gate level-appropriateness and price, but the book explicitly says story can override rarity. Hard cap: **3 attuned items per creature**, always.

**Monster Design (Ch 9)** — Quick Monster Stats: pick expected CR → pull AC/HP/attack/damage/save DC off the CR table → adjust → recompute final CR as the *average* of independently-derived defensive (HP/AC) and offensive (damage/attack-or-save-DC) ratings. Cheapest-to-most-effort customization ladder: reskin → weapon swap → add one trait → Quick Stats → full 20-step stat block.

**Downtime Activity Chassis (Ch 6)** — nearly every downtime activity follows days-spent (scaled to scope) → ability check → d100(+modifier) outcome table. Use this shape when inventing new downtime activities.

**Rest Pacing Dial (Ch 9)** — Standard (1hr/8hr) vs. Epic Heroism (5min/1hr, compensate with harder fights) vs. Gritty Realism (8hr/7days, favors intrigue-heavy play). Pick deliberately per campaign.

---

## Chapter Index

| # | Title | Key Frameworks |
|---|-------|----------------|
| [ch01](chapters/ch01-world-of-your-own.md) | A World of Your Own | Core Assumptions Inversion, Tiers of Play, World-Shaking Events, Renown/Piety |
| [ch02](chapters/ch02-creating-a-multiverse.md) | Creating a Multiverse | Cosmological models, portal design, Outer Plane optional rules |
| [ch03](chapters/ch03-creating-adventures.md) | Creating Adventures | XP thresholds, Adventuring Day, location/event-based build order, Mystery/Intrigue |
| [ch04](chapters/ch04-creating-nonplayer-characters.md) | Creating Nonplayer Characters | Ten Sentences, Villain Scheme, Loyalty score |
| [ch05](chapters/ch05-adventure-environments.md) | Adventure Environments | Dungeon build stack, trap severity framework, wilderness survival |
| [ch06](chapters/ch06-between-adventures.md) | Between Adventures | Downtime chassis, campaign tracking, crafting/selling/renown |
| [ch07](chapters/ch07-treasure.md) | Treasure | Rarity, attunement, hoard generation, sentient items, artifacts |
| [ch08](chapters/ch08-running-the-game.md) | Running the Game | Typical DCs, advantage/disadvantage, social interaction, chases, madness, XP models |
| [ch09](chapters/ch09-dungeon-masters-workshop.md) | Dungeon Master's Workshop | Monster/spell/item/race/background creation, rest & healing variants |
| [appA](chapters/appA-random-dungeons.md) | Random Dungeons | Two-pass procedural dungeon generation |
| [appB](chapters/appB-monster-lists.md) | Monster Lists | Environment × CR monster index |
| [appC](chapters/appC-maps.md) | Maps | Sample map reuse guidance |
| [appD](chapters/appD-dm-inspiration.md) | DM Inspiration | Craft-improvement reading list |

## Topic Index

- **Advantage/disadvantage** → ch08
- **Artifacts** → ch07
- **Attunement** → ch07, ch09
- **Between-adventures / downtime** → ch06
- **Chases** → ch08
- **Combat encounter difficulty / XP thresholds** → ch03
- **Cosmology / planes** → ch02
- **Curses / cursed items** → ch07
- **DCs (setting difficulty)** → ch08
- **Downtime activities** → ch06
- **Dungeon design** → ch05, appA
- **Encounter tables (random)** → ch03, appB
- **Factions** → ch05
- **Homebrew (monsters/spells/items/races/backgrounds)** → ch09
- **Inspiration (mechanic)** → ch08
- **Madness** → ch08, ch09
- **Magic items** → ch07, ch09
- **Milestones / leveling models** → ch08
- **Monster creation / CR math** → ch09
- **NPC creation** → ch04
- **Renown / Piety** → ch01, ch06
- **Rest variants** → ch09
- **Sentient items** → ch07
- **Settlements** → ch05
- **Sanity / Honor scores** → ch09
- **Social interaction** → ch08
- **Tiers of Play** → ch01
- **Traps / hazards** → ch05, ch08, appA
- **Treasure tables** → ch07
- **Villains** → ch04
- **World building** → ch01, ch02
- **World-shaking events** → ch01

## Supporting Files

- [glossary.md](glossary.md) — all key terms with definitions
- [patterns.md](patterns.md) — all techniques and design patterns
- [cheatsheet.md](cheatsheet.md) — quick reference tables and decision guides

---

## Scope & Limits

This skill covers the 2014 5th Edition Dungeon Master's Guide content only — not the Player's Handbook, Monster Manual, Xanathar's Guide, Tasha's Cauldron, or the 2024 revised core rulebooks. For character-creation rules, consult the Player's Handbook; for full monster stat blocks, consult the Monster Manual. Combine with project-specific campaign notes for hands-on play. For rules beyond this book, check related skills or ask directly.
