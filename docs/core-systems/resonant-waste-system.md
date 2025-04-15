# Resonant Dissonance System

## Core Idea: Conservation as a World Law

> “The world remembers not just what you build—but what you waste.”

The Resonant Dissonance system transforms discarded items, forgotten materials, and idle waste into a living, evolving force in the world. It enforces a soft law of conservation, grounded in the themes of memory, decay, and resonance.

This is not punishment—it’s consequence.

---

## Design Goals

| Goal | Mechanic |
|------|----------|
| Encourage players to value all items | Dissonance → resonance → consequence |
| Discourage careless despawning | Visible side effects (haunts, rot, corruption) |
| Create immersive recycling/repurposing systems | Memory Recyclers, Organic Composter |
| Reward conservation | Tools gain memory efficiency, world balance maintained |
| Embed in world logic and lore | Woven into Echoes, CR Core, and dimensional systems |

---

## Mechanics Overview

### 1. **Resonant Dissonance Counter (Local)**
- Each chunk or region has an invisible “dissonance” meter
- Raised when:
    - Items despawn naturally
    - Corrupted materials are dropped
    - Unused rituals fizzle
- Lowered when:
    - Items are recycled or composted
    - Cleansing rituals are performed
    - Rift plants grow and stabilize a zone

### 2. **Resonant Waste Entity Spawns**
At high Dissonance thresholds, one of the following may manifest:

#### 🕷 Memory Beast
- Form: Golem-Spider hybrid made of forgotten blocks
- Scales in size based on despawn quantity
- Drops salvageable shards if defeated
- Possible mini-boss in high-Dissonance zones

#### 🍄 Fungus Aberrant
- Form: Spreading fungus that grows over terrain
- Slowly consumes structures or flora nearby
- Grows only when chunks are loaded
- Must be trimmed, purified, or ritual-burned

#### 👻 Resonant Wraith
- Form: Pale echo of discarded tools or items
- **Unkillable** – Can only be banished by ritual
- Haunts the player, sapping tool efficiency and dimming light
- Doesn’t harm the player—only follows, whispers, and unnerves

All mobs may be tied to corresponding dimensions in Echoes (Void, Decay, Echo Realms).

---

### 3. **Memory Recycler / Salvage Crafter**
- Takes junk items and breaks them into:
    - **Resonant Dust** → base magical material
    - **Echo Shards** → compressed, purified memory fuel
- These are used for:
    - Tool repair
    - Low-tier ritual fuel
    - Cleansing ambient Dissonance

---

### 4. **Organic Composter**
- Takes natural blocks, mob drops, food waste
- Produces:
    - **Fertile Catalyst** (bio magic fuel)
    - **Dimensional Root Seeds** (plants that suppress Dissonance)
- Planting these plants in corrupted areas reduces Dissonance gradually

---

### 5. **Despawn Echo Mechanic**
- When a rare item despawns, a nearby stone or ruin may **“remember”** it
- Possible outcomes:
    - Short-lived vision or lore fragment
    - Phantom item replica (can’t be picked up, only studied)
    - Ritual site activated to recover it through sacrifice

---

### 6. **Ritual of Binding**
- Altar that prevents despawn within a set radius
- Items instead become “Memory Phantoms” (semi-real echoes)
- Echoes can be stored or converted—but only under resonance balance
- If ritual is unstable, items corrupt or summon a Wraith

---

### 7. **Resonance Mass System**
- Every item has a hidden **Resonance Mass** stat (similar to EMC)
- High-mass items impact Dissonance more when wasted
- Could be visualized via tooltips, particle colors, or a scan tool

---

## Implementation Plan

| Phase | Content |
|-------|---------|
| **CR Core** | Dissonance tracker, Resonance Mass tagging, Ritual system hooks |
| **Echoes** | Memory Wraiths, fungus corruption, lore zones with remembered decay |
| **Standalone Module** | “Decay of Matter” or “Auroral Conservation” – Rituals, plants, full system exposure |

---

## Integration Points

- FTB Quests: Track entropy events, offer recycling goals
- Patchouli: Teach the system with visual feedback and in-world signs
- Biome Tagging: Certain biomes more vulnerable to decay (swamps, ruined zones)

---

> _“Decay is not death—it is memory without form. But all memory, if left unanchored, becomes a haunt.”_

This system ties personal choice to world behavior, and asks: what do you leave behind?

