---
name: vintage-dnd-art
description: Generate artwork, character portraits, scene moments, and tokens in classic 1980s-1990s TSR-era Dungeons & Dragons fantasy art style (Larry Elmore, Keith Parkinson, Jeff Easley). Use whenever the user asks for vintage, retro, old-school, or TSR D&D fantasy art, oil painted D&D scenes, or classic rulebook/box-art illustrations.
---

# Vintage D&D Art Generator

A skill for generating fantasy artwork and character portraits adhering to the traditional, hand-painted aesthetic of classic 1980s and 1990s TSR Dungeons & Dragons publications.

## When to Use

* Generating D&D or fantasy character portraits, tokens, or party scenes with an authentic retro/vintage feel.
* When generating scenes from character dossiers in `characters/` or scene blueprints in `prompts/`.
* When the user asks for "old school D&D art", "TSR style", "classic fantasy oil painting", or references artists like Larry Elmore, Keith Parkinson, or Jeff Easley.
* Creating campaign illustrations that strictly avoid glossy, smooth, digital 3D/CGI render aesthetics.

## Core Aesthetic Principles

### 1. Traditional Medium & Texture
* **Primary Media:** Oil on canvas, gouache, or watercolor on heavy illustration board.
* **Physical Details:** Visible layered brushstrokes, dry-brush scumbling on stone/cloth, subtle impasto, and tactile paper/canvas grain.
* **Surface Quality:** Matte or semi-matte finish. Avoid plastic sheen, digital bloom, or airbrushed gradients.

### 2. Natural Ambient Lighting & Palette
* **Palette:** Rich, warm, earthy tones (raw umber, ochre, forest greens, terracotta, deep turquoise, muted gold).
* **Lighting:** Realistic directional or ambient light (torchlight, campfire, filtered overcast daylight, storm light). Shadows should be warm and deep, not pitch black or saturated neon.

### 3. Anatomical Realism & Practical Detailing
* Realistic proportions and grounded equipment. Armor and clothing show wear, creases, and scuffs.
* Magical effects (sparks, lightning, runes) should look hand-painted with fine brushwork rather than digital neon glow overlays.

## Prompt Construction Guidelines

When calling image generation tools or constructing prompts for D&D imagery, structure the prompt with these components:

1. **Subject & Scale:** Specific fantasy character, race, class, physical height relative to surroundings, pose, and expression.
2. **Attire & Armament:** Material textures (creased leather, forged iron, weathered cloth, feathers), specific colors, and signature weapons.
3. **Environment & Atmosphere:** Specific setting, time of day, atmospheric effects (dust motes, mist, wood smoke, rain).
4. **Style Keywords (MANDATORY):**
   `"Vintage 1980s D&D fantasy illustration, classic TSR box art aesthetic, traditional oil painting on textured canvas, visible fine brushwork, earthy palette, rich matte finish, warm ambient lighting, in the style of Larry Elmore and Keith Parkinson."`
5. **Negative Constraints (MANDATORY):**
   `"Avoid: digital 3D render, CGI, glossy plastic skin, modern video game splash art, hyper-shiny reflections, neon rim lighting, smooth digital airbrush."`

## Example Prompt Pattern

```text
A full-body fantasy illustration of a Halfling rogue arcane trickster standing proudly in a rustic wooden tavern. Slender 3-foot stature, prominent groomed dark brown mustache, green eyes, confident theatrical smirk while twirling mustache tip. Wearing tailored turquoise studded leather with warm orangey-gold trim and an oversized wide-brimmed turquoise hat with an orange-gold feather. Small sparks of white-blue electricity crackle softly between fingers. Vintage 1980s D&D fantasy illustration, classic TSR box art aesthetic, traditional oil painting on textured canvas, visible fine brushwork, earthy palette, rich matte finish, warm hearth lighting, in the style of Larry Elmore and Keith Parkinson. Avoid digital 3D render, CGI, glossy plastic skin, neon bloom.