---
name: vintage-dnd-art
description: Generate artwork, character portraits, scene moments, and tokens in classic 1980s-1990s TSR-era Dungeons & Dragons fantasy art style (Larry Elmore, Keith Parkinson, Jeff Easley, Clyde Caldwell). Use whenever the user asks for vintage, retro, old-school, or TSR D&D fantasy art, oil painted D&D scenes, or classic rulebook/box-art illustrations.
---

# Vintage D&D Art Generator (1980s TSR Masters Edition)

A skill for generating fantasy artwork and character portraits adhering strictly to the traditional, hand-painted aesthetic of classic 1980s and early 1990s TSR *Dungeons & Dragons* module covers and rulebooks (Larry Elmore, Keith Parkinson, Jeff Easley, Clyde Caldwell).

## When to Use

* Generating D&D or fantasy character portraits, tokens, or party scenes with an authentic 1980s TSR book-cover feel.
* When generating scenes from character profiles in `characters/` or scene blueprints in `prompts/`.
* When the user asks for "old school D&D art", "TSR style", "classic fantasy oil painting", or references artists like Larry Elmore, Keith Parkinson, Jeff Easley, or Clyde Caldwell.

## Core Aesthetic Pillars & Anti-Digital Rules

### 1. Strict Grounded Anatomical Realism (Anti-Caricature Rule)
* **Adult Realistic Proportions:** All characters—including miniature races like halflings, gnomes, and dwarves—must have realistic, weathered, grounded adult human facial proportions, small realistic eyes, and serious anatomical structure (in the tradition of Larry Elmore and Boris Vallejo).
* **Avoid Whimsical Trigger Words:** Never use words like *"impish", "whimsical", "bouncy", "exuberant",* or *"cartoonish"* in image prompts, as these trigger oversized heads, big Pixar/Hearthstone eyes, and rosy caricature cheeks. Translate theatricality into grounded posture and period-accurate expression.

### 2. High-Contrast Chiaroscuro & Tenebrism (Anti-Studio Lighting Rule)
* **Directional Theatrical Lighting:** Scenes must be lit by a single strong directional light source (golden-hour sunbeam, torchlight, brazier glow, or storm flash) while 40–50% of the background falls into deep, murky burnt-umber or slate shadow.
* **Lost-and-Found Painterly Edges:** Forms, boots, and cloaks should softly merge into surrounding shadows, mist, or stonework without crisp digital cutout outlines.

### 3. Traditional Medium, Matte Pigment & Print Grain (Anti-Shader Rule)
* **Primary Media:** Oil on fine-weave canvas or gouache and acrylic on heavy illustration board.
* **Surface Tactility:** Heavy dry-brush scumbling on stone, bark, and mist contrasted with fine sable brushwork on anatomy and scales.
* **Desaturated Chalky Matte Palette:** Translate bright digital colors into muted, historical oil pigments (e.g., use *"muted slate-turquoise weathered suede and antique ochre"* instead of *"vibrant turquoise and bright gold"*). Highlights on metal and leather must use opaque cream and pale yellow paint rather than glossy 3D specular reflections.
* **Physical Print Artifacting:** Include subtle 1983 offset lithograph book print grain, visible canvas tooth, and slight paper texture.

### 4. Opaque Painted Magic (Anti-Photoshop Overlay Rule)
* **Pigment-Only Spell Effects:** Lightning, sparks, fire, and glowing weapons must be described as physical paint layers—*"rendered purely with opaque chalk-white and pale-yellow oil paint strokes with a soft feathered airbrush halo"*. Never allow sharp fractal digital lightning or neon post-process bloom overlays.

### 5. Candid Narrative Staging (Anti-Lineup Rule)
* **Book-Cover Framing:** Use low camera angles, over-the-shoulder action framing, or layered foreground/midground/background depth planes separated by creeping ground fog or brazier smoke.
* **No Camera Eye Contact:** Characters must look into the scene, at each other, or at the objective—never standing in a flat horizontal row staring directly into the camera lens.

## Mandatory Prompt Construction Blueprint

1. **Medium & Print Header (MANDATORY):**
   `"1983 TSR Dungeons & Dragons module cover illustration, traditional oil and gouache painting on textured illustration board by Larry Elmore, Keith Parkinson, and Clyde Caldwell. Authentic 1980s offset lithograph print scan with subtle paper tooth, muted earthy underpainting in burnt umber and raw sienna, chalky matte finish, and heavy dry-brush scumbling."`
2. **Candid Composition & Chiaroscuro Lighting:**
   Specify low/narrative camera angle, directional key light, deep umber background shadows, lost-and-found edges, creeping ground mist, and `"nobody looking at the camera"`.
3. **Subjects & Grounded Anatomy:**
   Describe each subject with strict relative scale anchors (e.g., halflings strictly waist-high to humans) and explicitly enforce: `"CRITICAL PROPORTIONS: Realistic, grounded adult human facial anatomy, small realistic eyes, weathered skin texture—no oversized head, no cartoon features."`
4. **Pigment-Based Gear & Magic:**
   Use muted, lived-in material descriptors (scuffed hide, dented matte steel, weathered suede) and specify that any magical effect is painted with opaque pale-yellow/chalk-white brushstrokes.
5. **Negative Constraints (MANDATORY):**
   `"Avoid: modern digital painting, Dungeons & Dragons 5e concept art, Hearthstone style, oversized heads, Pixar or cartoon expressions, big eyes, looking at the camera, flat even studio lighting, crisp dark outlines, digital fractal lightning overlays, glossy satin leather, mirror-chrome reflections, CGI, Unreal Engine."`