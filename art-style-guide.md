# Visual Style Guide: Classic 1980s TSR Fantasy Oil Art

Use this guide as the mandatory baseline whenever generating artwork (portraits, scene moments, tokens, or double-page spreads) for our campaign[cite: 10].

---

## 🎨 Aesthetic Intent
We strictly avoid the glossy, hyper-clean digital rendering, cartoon proportions, and flat "studio" lighting typical of modern 5e concept art, board games, and AI defaults[cite: 10]. Our target aesthetic is the authentic, hand-painted fantasy book and module cover art of **1980s TSR-era Dungeons & Dragons**—specifically the masterworks of **Larry Elmore, Keith Parkinson, Jeff Easley, and Clyde Caldwell**[cite: 8, 10].

---

## 🏛️ The 5 Core Visual Pillars (TSR vs. Modern Digital)

### 1. Strict Grounded Anatomical Realism (Anti-Caricature Rule)
* **Adult Realistic Proportions:** Every character—including smaller races like halflings and dwarves—must be rendered with realistic, weathered adult human facial proportions, small realistic eyes, and grounded skeletal structure (in the tradition of Larry Elmore and Boris Vallejo)[cite: 20].
* **Word Replacement Rule:** Never use whimsical personality prompts like *"impish grin," "bouncy," "exuberant,"* or *"cartoonish"*—these cause AI models to generate oversized heads, big Pixar/Hearthstone eyes, and rosy caricature cheeks. Describe theatricality through **posture and action** while keeping facial anatomy gritty and realistic.

### 2. High-Contrast Chiaroscuro & Tenebrism (Anti-Studio Lighting Rule)
* **Directional Key Light:** Scenes must be lit by a single strong, theatrical light source (a golden-hour sunbeam, flickering brazier, hearth fire, or storm flash) while **40–50% of the background falls into deep, murky burnt-umber or slate shadow**.
* **Lost-and-Found Edges:** Do not allow crisp dark outlines around characters or gear. Boots, cloaks, and armor edges should softly merge into surrounding shadows, stonework, or creeping ground mist.

### 3. Traditional Medium, Matte Pigment & Print Grain (Anti-Shader Rule)
* **Physical Media:** Oil painting on fine-weave canvas or gouache and acrylic on heavy illustration board[cite: 10].
* **Brushwork Contrast:** Use heavy dry-brush scumbling and stippling on stone, tree bark, and mist, contrasted against tight fine-sable brushwork on skin, scales, and leather[cite: 10].
* **Chalky Matte Desaturation:** Translate saturated digital color descriptions into muted oil pigments (e.g., prompt *"muted slate-turquoise weathered suede and antique ochre trim"* instead of *"bright turquoise leather and shiny gold"*). Highlights on steel and gold must use opaque cream and pale yellow pigment rather than glossy 3D specular reflections[cite: 10].
* **1980s Print Artifacting:** Include subtle 1983 offset lithograph book print grain, visible canvas tooth, and slight halftone paper texture.

### 4. Opaque Painted Magic (Anti-Photoshop Overlay Rule)
* **Pigment-Only Spell Effects:** Lightning, static sparks, fire, and glowing blades must look physically painted onto the board[cite: 10, 20]. Always specify: *"magical energy rendered purely with opaque pale-yellow and chalk-white oil paint brushstrokes and a soft feathered airbrush halo—no sharp digital fractal lightning overlays or neon bloom."*

### 5. Candid Narrative Staging (Anti-Lineup Rule)
* **Book-Cover Composition:** Use low camera angles, over-the-shoulder action framing, or theatrical pyramid staging with distinct foreground, midground, and background planes separated by painted ground fog.
* **No Eye Contact with Camera:** Characters must look into the scene, at each other, or at a point of interest. Never line characters up in a flat horizontal row staring directly into the camera lens.

---

## 📐 Compositional Archetypes (Master Reference Templates)

* **The Looming Threat (Parkinson / Elmore Landscape Style):** Low camera angle; massive hazard or dramatic sky towering in the upper two-thirds framed by gnarled trees or crags, with adventurers grounded in a misty foreground.
* **The Over-the-Shoulder Duel (Elmore "Red Box" Style):** Tight framing from behind a foreground character's shoulder; cool-toned foreground character contrasting against a warm-toned threat or focal point in the upper frame.
* **The Pulp Altar Tableau (Caldwell / Easley Symmetrical Style):** Symmetrical, theatrical staging on stepped stone architecture; dark chiaroscuro background columns, central focal character, and dry-brushed smoke or mist pooling across the lower steps.

---

## 🔑 Mandatory AI Prompt Blueprint

Structure every prompt using these five blocks in order:

```text
1. Medium & Print Header (MANDATORY):
1983 TSR Dungeons & Dragons module cover illustration, traditional oil and gouache painting on textured illustration board by Larry Elmore, Keith Parkinson, and Clyde Caldwell. Authentic 1980s offset lithograph print scan with subtle paper tooth, muted earthy underpainting in burnt umber and raw sienna, chalky matte finish, and heavy dry-brush scumbling.

2. Candid Composition & Chiaroscuro Lighting:
[Specify low/narrative camera angle, directional key light source, 50% of background in deep umber shadow, lost-and-found painterly edges, creeping ground mist, and "nobody is looking at the camera."]

3. Subjects & Grounded Anatomical Realism:
[Describe characters and strict relative scale anchors. For small races, include: "CRITICAL PROPORTIONS: Realistic, grounded adult human facial anatomy at miniature scale—small realistic eyes, weathered skin texture, no oversized head, no cartoon features."]

4. Pigment-Based Gear & Magic:
[Describe lived-in, scuffed, muted fabrics/metals. For magic/lightning, include: "rendered purely with opaque chalk-white and pale-yellow oil paint brushstrokes and a soft feathered airbrush glow."]

5. Negative / Avoid Keywords (MANDATORY):
Avoid: modern digital painting, Dungeons & Dragons 5e concept art, Hearthstone style, oversized heads, Pixar or cartoon expressions, big eyes, looking at the camera, flat even studio lighting, crisp dark outlines, digital fractal lightning overlays, glossy satin leather, mirror-chrome reflections, CGI, Unreal Engine.