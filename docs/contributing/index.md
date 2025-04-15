# Contributing to Coherent Recursion

Welcome, world-shaper! 🎉

Whether you're a coder, designer, writer, artist, or just an enthusiastic player, we’re excited to have you contribute to **Coherent Recursion**—a modular evolution of Minecraft grounded in narrative design, resonance-driven systems, and player immersion.

---

## 💡 Project Philosophy (TL;DR)

Coherent Recursion is:
- A framework, not just a modpack
- Modular by design (content is opt-in, unlockable, isolated)
- Narrative-rooted (resonance, memory, and meaning)
- Focused on immersive, thoughtful gameplay—not feature sprawl

We prioritize **clarity, cohesion, and player experience** in every contribution.

---

## 🔧 How to Get Started

### 1. Fork the Repo
Create your own fork of `X18Tec/Coherent-Recursion` and clone it locally.

### 2. Choose Your Focus
You can contribute to:
- 🧩 **New Modules** (tools, biomes, mobs, systems)
- ⚙️ **CR Core** (framework logic, APIs, registries)
- 📘 **Documentation** (lore, wiki content, Patchouli books)
- 🧪 **Testing & Bug Reports**
- 🎨 **Assets** (models, textures, icons, sound design)

See [Module Progression Map](./cr_module_progression_map.md) for ideas.

### 3. Review the Design Docs
Start with these essentials:
- [Core Philosophy](./cr_core_philosophy.md)
- [Friction → System Mapping](./cr_friction_to_system_map.md)
- [Project Overview](./coherent_recursion_overview.md)

These define how and why we design the way we do.

---

## 📦 Submitting a Module

Each module should:
- Be self-contained (its own namespace + data folders)
- Register content only when unlocked
- Integrate with CR Core APIs (for gating, resonance, dimension control)
- Include Patchouli pages and/or quest entries
- Follow naming standards and code style guide

Use `/modules/MODULE_NAME/` for code + assets.

### Example Folder Structure
```
/modules/
  memory_nexus/
    data/
    assets/
    patchouli_books/
    recipes/
    mixins/
    README.md
```

### Module Checklist
- [ ] Module.json defines metadata, dependencies, unlock type
- [ ] All items/blocks use the `cr.MODULENAME_` prefix
- [ ] Patchouli book created or updated
- [ ] Code includes Javadoc-style comments
- [ ] Any added dependencies are noted in PR

---

## ✏️ Writing Docs & Lore

We love well-written, immersive entries! To contribute lore:
- Submit `.md` or `.txt` files to `/docs/lore/`
- Keep narrative tone consistent with existing entries
- Use memory/resonance metaphors (see [Core Philosophy](./cr_core_philosophy.md))
- Short fragments are just as valuable as full stories

---

## 📜 Coding Standards
- Java 17+ (NeoForge 1.21.1)
- Use CR Core systems for gating/registration where applicable
- Prefer data-driven over hardcoded features
- Avoid global static registries
- All PRs should include at least **1 test world snapshot** or example

---

## 🧪 Testing Guidelines
- Test both client and server environments
- If your module adds a dimension or progression lock, test with default player progression
- Report any dependencies that behave unexpectedly under CR Core
- Include crash reports or screenshots in issues

---

## 🙌 Community Values
- Be respectful and curious
- Ask before starting large changes
- Document decisions and designs in PR descriptions
- Credit others when building on their work
- Keep discussion constructive and ideas-focused

---

## 💬 Where to Ask Questions
- **Discord** (invite coming soon!)
- GitHub Discussions
- Comment in issues or PRs

---

## 🏗️ Contributor Recognition
All contributors will be credited:
- In-game via `/credits` and main menu
- On the GitHub page + wiki
- In module-specific Patchouli books (if applicable)

Significant contributors may be invited to join the **CR Dev Circle**—our core builder and module architect team.

---

## ✨ Thank You
This project is built on memory—and you’re now part of it.

> *“The world remembers those who shape it.”*

