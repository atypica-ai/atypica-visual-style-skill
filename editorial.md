# Editorial Mode — Luminous Abstraction

Used for: research report covers, blog post covers, podcast covers, social media sharing images.

Purpose: Convey energy, mood, and vitality through abstract beauty. Stop the scroll on social media. Make people save the image for its beauty alone.

**The most important rule: NEVER illustrate the topic literally.** The image is about ENERGY and MOOD, not about depicting the subject matter. A study about tourism must NOT show landmarks. A study about hardware must NOT show circuits. A study about food must NOT show food.

## Why This Works

Every image in this mode is a real optical phenomenon: light passing through frosted glass, a meadow shot completely out of focus, a flower petal so close the lens can't resolve it. The model understands these as physical situations — it generates the light falloff, the chromatic aberration, the grain that a real camera would produce. This is what separates our covers from "AI gradient art."

---

## Visual Styles

Pick ONE per image. Weights indicate how often each should appear across a collection.

### Style A — Bokeh Photography (12%)

A real-world organic scene (wildflowers, sunlit leaves, grass, dew) shot COMPLETELY out of focus. Nothing is sharp — the entire image is a soft blur of color and light conveying motion and vitality. Shot on vintage 35mm film (Kodak Gold, Fuji Superia) with heavy visible grain. Warm golden-green-yellow tones. Strong backlight creates a dreamy glow. Feels like speed — like looking out a train window at a rushing landscape.

Key: the subject is REAL (grass, flowers, light through leaves) but the lens makes it abstract. This is real optics, not a filter.

### Style B — Frosted Glass Gradient (30%)

Purely abstract — NO objects, NO shapes, NO layers. A color gradient filling the entire frame with clearly visible color movement: must shift noticeably from one hue to another (e.g., left is cool teal, center has a warm glow, right fades to cream). NOT a flat monotone wash — there must be 2-3 distinct color zones blending softly. Fine sandblasted matte micro-grain texture like premium frosted glass. One area has a PRONOUNCED warm glow as if concentrated sunlight hits the frosted surface from behind.

Key: describe it as light passing through a physical material (frosted glass, resin, ice). The model renders the light physics.

### Style C — Vivid Macro Flora (8%)

Extreme close-up of a single flower or petal filling most of the frame. Ultra-shallow depth of field — only one thin edge in focus, the rest dissolves into luminous color. Bright, vivid colors (coral-pink, peach, lavender). Must feel ABSTRACT — so close and so blurred it becomes a color field, not an identifiable object. Subtle film grain.

Key: a real macro lens at f/1.4, so close to a real flower that the image becomes pure color.

### Style D — Abstract Grain Landscape (20%)

Abstract organic shapes vaguely suggesting natural landscape (rolling hills, moss fields) but completely non-representational. The ENTIRE image is constructed from dense colored noise — like pointillism or colored sand. NO smooth areas anywhere. Colors (moss green, raw umber, ochre, dark amber) only emerge at macro level; at close range it's pure stipple/grain. The grain IS the medium, not a filter overlay.

Key: the texture is the subject. Describe it as colored sand, pointillist dots, expired film pushed to extremes.

### Style E — Structured Color Surface (30%)

A large dominant color block (70-80% of frame) + secondary accent color (20-30%). The two zones meet at a soft, blurred boundary with organic shape (wave edge, cloud form, gentle curve — NOT a straight line). Low-saturation, modern, refined. Fine matte texture. Feels like a premium Material Design hero section.

Key: describe it as a physical surface (canvas, matte paper, plaster wall) with light hitting it from one side.

---

## Color Palettes

Pick ONE per image. Never repeat within a batch.

- Ice blue + cream: `#A1C4FD -> #C2E9FB`
- Sage green + soft gold: `#C8E6C9 -> #FFF9C4`
- Lavender + warm peach: `#E1BEE7 -> #FFCCBC`
- Deep cyan + mint: `#80DEEA -> #E0F7FA`
- Coral pink + sky: `#F8BBD0 -> #BBDEFB`
- Amber + olive: `#FFE0B2 -> #DCEDC8`
- Champagne + blush: `#FFF9C4 -> #FCE4EC`
- Slate + cool white: `#B0BEC5 -> #ECEFF1`

Rules:
- 2-3 dominant hues per image, each with purpose
- Bright and warm (except Style D which can be earthier)
- Avoid: neon, pure black, harsh contrast, corporate blue, tech-startup purple

---

## Texture

Every image must have visible texture. Match to style:

| Style | Texture |
|-------|---------|
| A (Bokeh) | Heavy analog film grain, coarse, like ISO 6400+ |
| B (Frosted Glass) | Fine sandblasted matte grain, like premium frosted glass |
| C (Macro Flora) | Subtle film grain, present but light |
| D (Grain Landscape) | Extremely heavy — grain IS the medium |
| E (Color Surface) | Fine matte texture, subtle frosted grain |

---

## Text Treatment

- Extract 1-3 specific English keywords from the topic (concrete nouns, not generic)
- Text must be LARGE and BOLD — 20-30% of frame width minimum
- Placement: centered, lower-left, or upper-right (vary across images)
- Typography: bold sans-serif
- Color: WHITE is default. Only dark charcoal when background is near-white
- NEVER use non-Latin script
- If background is minimal, text IS the visual anchor — never tiny text in a corner

---

## Prompt Structure

```
[Style declaration and core visual description — what physical situation creates this image]
[Color palette with hex values]
[Texture specification — what physical material/film stock]
[Text: keyword(s), size, placement, color]
[Composition notes]
[Prohibitions relevant to this topic — what NOT to show]
```

---

## Example Prompts

**Style A — Bokeh Photography:**
```
Wild meadow with small yellow wildflowers, extremely shallow depth of field
on vintage lens. Foreground flowers are soft golden blurs, background dissolves
into warm green-gold wash. Strong backlit sunlight creating dreamy glow through
petals. Heavy analog film grain like expired Kodak Gold 200. Colors: golden
amber, chartreuse, warm cream. Upper-left: bold italic white serif text
"Decoder" as brand mark. Lower-left: two lines white sans-serif "Why Synthetic
Consumers" and "Feel Like Real People". 16:9 landscape.
```

**Style B — Frosted Glass Gradient:**
```
Out-of-focus abstract photograph. Soft bokeh color field blending warm sage
green and muted gold tones. Blurred organic shapes with gentle light diffusion.
Film grain texture throughout. No sharp edges, no icons. Dreamy atmospheric
quality like light passing through frosted glass. Bold white text 'What
Enterprises Really Ask' in the lower-left area, clean sans-serif typeface,
slightly transparent. 16:9 landscape.
```

**Style C — Vivid Macro Flora:**
```
Close-up of a large blooming flower filling the frame, shot with extremely
shallow depth of field at wide-open aperture. Petals in vivid coral-pink and
warm peach with iridescent lavender reflections on translucent edges. Background
is clean periwinkle-lavender with a second flower blurred into abstract color
in upper-right. Bright, alive, optimistic spring morning light. Luminous and
airy, no dark shadows. Subtle film grain. Bold white sans-serif text
"Multi-Agent Engine" centered large, slightly transparent over bright areas.
16:9 landscape.
```

**Style D — Abstract Grain Landscape:**
```
Abstract color field with extremely heavy film grain texture. Organic flowing
shapes in deep moss green and warm amber tones bleeding into each other like
ink in water. Analog 35mm expired film quality. Moody earthy atmosphere. No
sharp edges, no icons. White serif text "Multi-Agent Research Engine" centered
vertically and horizontally, medium weight. 16:9 landscape.
```

**Style E — Structured Color Surface:**
```
Smooth frosted glass surface photographed in extreme close-up. The glass has
a fine matte sandblasted texture with visible micro-grain like premium
stationery paper. Behind the glass, soft warm light creates a gentle gradient
from pale sage green on the left to muted gold-yellow on the right, with a
subtle warm glow in the center where light concentrates. The colors bleed and
shift organically. In the lower-left area, large bold text in two styles:
"Research" in white bold sans-serif, and "Engine" directly below in white
bold sans-serif at slightly lighter weight. 16:9 landscape format.
```

---

## Anti-Patterns

- Literal illustration of the topic (no landmarks, circuits, food photos)
- Sharp, recognizable, photorealistic objects or scenes
- Line illustrations, flat vector art, infographics
- 3D renders, floating objects, tech aesthetics
- Neon gradients, drop shadows, glowing effects
- Stock photography composition (staged, studio lighting)
- Small text in corners of empty images
- Keyword stuffing ("abstract, bokeh, 8k, minimal, elegant")
- Missing texture instruction
- Flat monotone (must have visible color movement)

---

## Quality Check

Before outputting, verify:
- Would this look at home on the cover of Kinfolk, Cereal, or an Anthropic blog post?
- Is the texture visible and tactile?
- Is there ANY risk of literal topic illustration?
- Would someone save this image for its beauty alone?
