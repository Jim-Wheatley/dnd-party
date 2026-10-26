# 🐉 Party Chronicles & Character Dossiers

Welcome to our campaign repository! This project serves as our party's single source of truth for character appearances, story beats, and visual evolutions over time.

By keeping each character's visual baseline and physical changes in Markdown, we track our campaign's living history and ensure everyone can generate consistent, hand-painted fantasy artwork across our adventures.

---

## 📁 Repository Structure

```text
.
├── README.md                                           # You are here! Table rules & guide
├── template.md                                         # Blank template for new characters & companions
├── art-style-guide.md                                  # Visual style guide (TSR / Vintage 80s oil art)
├── skills/                                             # Reusable AI Agent skill definitions
│   └── vintage-dnd-art.md                              # Skill definition for classic TSR-era art
├── characters/                                         # Individual player and companion dossiers
│   ├── dwarf-fighter-paladin-camdyn.md                 # Camdyn à Adair
│   ├── elf-cleric-galarald.md                          # Galarald Aexidor (In Memoriam)
│   ├── half-elf-sorcerer-warlock-elios.md              # Elios
│   ├── halfling-rogue-arcane-trickster-pantral.md      # Pantraal Y Galdas
│   ├── human-bard-tahner.md                            # Tânher the Elder
│   └── human-ranger-druid-baldan.md                    # Baldan Zumfaren & Yer Bastid
├── prompts/                                            # Reusable image generation blueprints
│   ├── prompt-trio-field-portrait.md                   # Baldan, Yer Bastid & Pantraal trail shot
│   ├── prompt-frozen-amphitheater-climax.md            # The DC 30 performance climax scene
│   ├── prompt-party-tavern-gathering.md                # Full party lined up at the tavern bar
│   └── prompt-pantral-stage-profile.md                 # 1:1 square acrobatic stage finale
└── assets/                                             # Generated art, portraits, tokens, and animations
    ├── portraits/
    └── key_moments/
```

---

## 🚀 Quickstart: Updating Your Character

You don't need deep Git expertise to contribute—just edit your `.md` file directly on GitHub or through your favorite editor!

### 1. After a Game Session
1. Open your file in `characters/[your-character-filename].md`.
2. Did something memorable happen? Add a bullet under **`## 📖 Story Beats & Character Growth`**.
3. Did your character gain a scar, new gear, a haircut, or a curse? Add an entry under **`## 🩹 Physical Changes, Scars & Relics`**.
4. Commit your changes (e.g., `git commit -m "docs(camdyn): add white streak from time stairs"`).

### 2. Creating a New Character or Companion
1. Copy `template.md` into `characters/[your-character-filename].md`.
2. Fill in your **Visual Baseline** (colors, silhouette, facial features, signature weapons, and scale anchors).
3. Commit and push directly to `main` or open a PR.

---

## 🎨 Visual Style Guide & Skills

All official party artwork generated for this repository follows a cohesive visual aesthetic inspired by classic 1980s and 1990s TSR D&D fantasy art (Larry Elmore, Keith Parkinson, Jeff Easley).

* **Aesthetic Standard:** Traditional oil painting on textured canvas, visible brushwork, earthy palettes, warm ambient lighting, and grounded equipment.
* **Negative Constraints:** We strictly avoid digital 3D/CGI renders, glossy plastic skin, neon lens flares, and modern anime styling.
* **Style Documentation:** See [`art-style-guide.md`](./art-style-guide.md) for full medium guidelines and negative prompt parameters.
* **Agent Skill:** If generating art with Gemini, Antigravity, or other AI agents, load [`skills/vintage-dnd-art.md`](./skills/vintage-dnd-art.md) to automatically inject these rules and scale anchors into generation sessions.
* **Pre-Built Prompts:** Check [`prompts/`](./prompts/) for ready-to-run scene blueprints and portrait prompts.

---

## ⚔️ Party Roster

| Character | Ancestry & Class | Archetype | Player | Status |
| :--- | :--- | :--- | :--- | :--- |
| **Baldan Zumfaren** | Human Ranger / Druid | Weathered scout, master marksman & sausage enthusiast (w/ Yer Bastid) | Player | Active |
| **Camdyn à Adair** | Mountain Dwarf Fighter / Paladin | Stalwart vanguard, master stoneworker, pipe smoker, bearer of the Amulet of Kalex | Player | Active |
| **Elios** | Half-Elf Sorcerer (Wild Magic) / Warlock | Deeply wise arcane polymath, mutated tentacle arm, emerald eye, unorthodox strategist | Player | Active |
| **Pantraal Y Galdas** | Halfling Arcane Trickster | Flamboyant performer, master showman, storm-singer | Alex | Active |
| **Tânher the Elder** | Human Bard (Tribal Skald) | Grumpy chronicler, self-proclaimed "Chosen One", relentless heckler | DM | Active |
| **Galarald Aexidor** | Elf Cleric of Kalex (War Domain) | Devout battle healer, flail wielder; laid to rest under the Living Tree | Former | 🕊️ Honored Ancestor |