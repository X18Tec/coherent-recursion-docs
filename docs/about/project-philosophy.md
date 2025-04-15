# Core Design Philosophy: Hostile Realms in Echoes of Aetherion

These aren't traditional adventure zones — they are shattered realms that expose the world's past sins and lost technologies. Each is built around a distinct resonance instability and features mobs that manifest from specific fractures in memory, aura, or dimensional logic.

## Dimensional Concepts & Atmospheres

### 1. The Verge of Echoes
*A realm where echoes resonate endlessly and time forgets how to flow.*

**Visual Style:** Faded, shifting color palette; echoing ambient sounds; slow-motion-like particle trails

**Biome Base:** Modified Void biome w/ Biomes You'll Go-style crystalline forests or ancient ruins

**Mechanics:**
- Movement slightly desynced (timing thrown off)
- Mobs phase in/out (spectral/transparent frames)
- Time-based puzzle mechanics (accelerate/rewind zones)

**Notable Mobs:**
- **Echo Drifters** – mimic player movement, flicker in/out
- **Resonant Remnants** – fragments of past adventurers, flicker between real and fake
- **Memory Leeches** – drain resonance from tools when hit

### 2. The Fractured Bastion
*An ancient tech vault torn apart by uncontrolled Mechanica resonance.*

**Visual Style:** Floating wreckage, lightning storms, corrupted red Create gears

**Biome Base:** End-like sky, ruined vault structures suspended over abyss

**Mechanics:**
- Unstable ground (fall risk)
- Redstone/machine pulses hurt over time (resonance overload)
- May require PneumaticCraft helmet or pressure system to enter

**Notable Mobs:**
- **Gearworn Sentinels** – corrupted AE2 robots or golems
- **Phase Loopers** – teleport in loops, only hittable mid-loop
- **Core Disruptors** – destroy player anchors/tools over time if not stopped

### 3. The Cradle of Silence
*The birthplace of Mnemonic energy, long overgrown and twisted.*

**Visual Style:** Dying forest, glowing plants, but eerily quiet — sound dampened

**Biome Base:** Silent swamp or deep forest retextured for spectral glow

**Mechanics:**
- Sound is muted or reversed
- Mob aggro range is unpredictable
- Echoes sometimes speak in reverse Patchouli glyphs

**Notable Mobs:**
- **Hollow Choirs** – floating veils that burst into memory screams when hit
- **Rootbound Wraiths** – emerge from trees and vines
- **Bloomless Watchers** – appear still, but move when not observed

### 4. The Shattered Veil
*Where the resonance broke and the void slipped in — a realm lost to entropy.*

**Visual Style:** Void with corrupted terrain chunks, glitch particles, purple haze

**Biome Base:** Nether-like gen with floating void shards, chaotic blocks

**Mechanics:**
- Players take slow aura damage unless protected by full resonance gear
- Flickering vision; structures may rotate
- Non-Euclidean pathways (illusionary blocks, recursive dungeons)

**Notable Mobs:**
- **Null Phages** – delete blocks/tools on contact
- **Flickerbeasts** – phase into player inventory and steal items
- **The Unmade** – humanoid bosses missing textures, speak backwards

## Mechanics Shared Across Realms

| Feature | Description |
|---------|-------------|
| Mnemonic Anchors | Must be built in-dimension to allow return travel |
| Resonance Saturation | Each realm "drains" or "floods" memory differently (buff/debuff) |
| Tool Degradation | Tools may gain or lose traits depending on mob interaction |
| Memory Contamination | Exposure to corrupted zones affects Codex readability temporarily |

## Dimensional Mob Design Philosophy

All mobs should represent failed echoes, corrupted tools, lost souls, or sentient fragments of resonance.

| Mob Class | Lore Flavor |
|-----------|-------------|
| Fragmentborn | Incomplete memory entities; drift and seek closure |
| Vault Golems | Mechanica protectors overridden by instability |
| The Repeating | Live in time loops; visual flicker, echo-speak |
| Worms of the Silence | Dig through forgotten soil; eat resonance itself |
| The Shamed | Ancient survivors, too broken to leave their realm |

## Technical & Mod Hooks

| System | Use |
|--------|-----|
| Structure Templates | Prebuilt ruined vaults, memory puzzles, echo traps |
| Particle Systems | Auroral flickers, glitch trails, resonance pulses |
| Biome Addons | Regions Unexplored + custom JSON + KubeJS scripting |
| Hostile Mob System | Spawn only in these realms; fully disabled in overworld |
| Dimension Access | Via high-tier Mnemonic Waypoint Gates or Sylvan Rites of Passage |