# Documentary Mode — Realistic Scenes & People

Used for: testimonial avatars, team photos, workspace shots, event imagery, case study visuals with people.

Purpose: Generate images of people in real environments that are indistinguishable from actual photographs or video stills. No AI smell.

## Core Insight

The difference between AI-looking and real-looking images is NOT about quality or resolution. It's about **what you describe**. AI images look fake because prompts describe **what the creator wants to achieve** (a portrait, a mood, an aesthetic) instead of **what a camera would see** (a person doing something, in a specific place, at a specific moment).

Write prompts like a film director describing a storyboard frame — not like a client writing a creative brief.

---

## The Storyboard Approach

You are narrating what a camera captures in a single frame. Describe the physical world objectively.

### Describe:
- **What the person is DOING** — a specific action mid-flow (typing, gesturing mid-sentence, scrolling phone, walking)
- **What they look like** — hair, clothing materials and colors, accessories, body type
- **Where they are in the frame** — center, left-third, slightly off-center
- **The space around them** — specific materials (leather, concrete, wood), specific objects that give character
- **One or two other people** — briefly, as context, not equally detailed

### Do NOT describe:
- **Moods or intentions** — "relaxed", "professional", "casual but polished"
- **Lighting effects** — "warm directional light", "dramatic shadows", "golden hour"
- **Photography terms** — bokeh, f-stop, aperture, lens model
- **Eye direction** — "looking at someone", "eyes directed at" (makes staring)
- **Detailed poses for everyone** — model over-executes into stiff arrangements
- **Foreground obstructions** — backs of heads, shoulders (always look fake)
- **Negative instructions** — "no X" imprints X
- **Screen/text content** — triggers fake UI rendering
- **Ethnicity labels** — "Chinese", "Caucasian" (triggers stereotypes). Describe features instead.

---

## What Makes Images Look AI

1. **Perfect symmetry** — subject dead center, equal space on both sides
2. **Uniform lighting** — everything evenly lit, no natural falloff
3. **Over-saturated color** — too vivid, too clean
4. **Smooth skin** — digital perfection
5. **Stock photo poses** — smiling at camera, arms crossed, "listening"
6. **Generic environments** — "modern office", "conference room" without specific character
7. **Clone faces** — multiple people with similar features
8. **Equal attention to everyone** — every person described in equal detail = arranged group photo

---

## The Single-Focus Principle

The most important lesson: **describe ONE person in detail, everyone else briefly.**

When you give every person equal description (hair, clothes, pose), the model renders a carefully arranged group portrait. When you focus on one person doing something and mention others in passing, it renders a candid moment where a camera happened to be.

Compare:

BAD (arranged):
> Three men sit on a sofa. The first has grey hair and glasses, wearing a blazer. The second has a red beard, wearing corduroy. The third has swept-back hair, wearing linen.

GOOD (candid):
> A man in his late 50s with grey-black hair and rectangular glasses is sitting on the edge of a desk, one hand raised mid-gesture — he is in conversation with students. Three or four students sit at the curved desk closest to him, some with laptops open.

---

## Controlling Texture & Color

### What works:
| Technique | Effect | Notes |
|-----------|--------|-------|
| "A still from a handheld video, slight grain, natural motion" | Documentary texture, candid feel | Best general-purpose opener |
| "Shot on Kodak Portra 400" | Natural skin tones, slight desaturation, fine grain | Good for warm natural scenes |
| "Shallow depth of field" | Background blur, subject isolation | Use sparingly — too much = portrait mode |
| "Shot at high ISO — visible fine noise" | Gritty texture in shadows | Good for indoor/dim scenes |

### What doesn't work:
| Technique | Problem |
|-----------|---------|
| "muted color" | Interpreted as DARK, not desaturated |
| "warm natural light" | Everything turns yellow/amber |
| "bright", "well-lit", "sunlit" | Overexposed stock photo look |
| "35mm film" alone | Triggers dramatic/thriller lighting |
| "slightly desaturated" | Inconsistent results |
| Director names (Kore-eda, etc.) | Controls palette but pulls ethnicity and set design |

### The Director Name Trap:
Director names are powerful palette controllers but have side effects. "Hirokazu Kore-eda" gives beautiful natural daylight and gentle grain — but makes everyone Asian and the space Japanese. Use only when the side effects align with your intent. Otherwise, describe the optical qualities directly ("fine grain, shallow depth of field, natural daylight from windows").

---

## Scene Design

### People need a reason to exist in the frame:
- They must be DOING something (working, speaking, walking past)
- Not observing, not standing idle, not "listening"
- Their action should relate to who they are

### Environments need specificity:
- "A meeting room" = generic AI
- "A lounge with tan leather armchairs, a concrete pillar, fiddle-leaf fig, exposed ducts" = a real place
- Give 3-5 specific materials/objects, then STOP — let the model fill the rest naturally
- The objects the model adds on its own (cables, mugs, notebooks, sticky notes) look more natural than ones you specify

### Multiple people:
- Focus on ONE person (the subject) — full description
- Others get ONE sentence max ("a colleague walks past in the background, blurred")
- Each person must look physically DIFFERENT if described (hair color, build, clothing)
- Don't describe their poses or what they're looking at

### The "facing left" trap:
- "All facing left" or "eyes directed at someone" = everyone stares rigidly in unison
- Better: describe body orientation for the subject only, let the model handle everyone else naturally
- Best: don't describe direction at all — just describe what the person is doing, the model infers body orientation from the action

---

## The Foreground Person Trap

NEVER describe partial people in the foreground (backs of heads, shoulders, silhouettes). Every time you do this, the model renders a giant, unnaturally shaped dark mass. If you want depth, describe the camera angle/position. The depth comes from lens characteristics, not from physical obstructions.

---

## Prompt Template

```
[Texture opener — "A still from a handheld video, slight grain, natural motion" or "Shot on Kodak Portra 400 — shallow depth of field, fine grain"]

[Subject — one person, physical appearance, what they're doing, where in frame]

[Context — 1-2 other people mentioned briefly]

[Space — 3-5 specific details about the environment, then stop]

[Closing — "No text, timestamps, or UI overlays on the image."]
```

---

## Working Examples

### Person at desk (candid work moment):
```
A still from a handheld video, slight grain, natural motion. A young woman
in her late 20s with long straight black hair past her shoulders and
thin-framed glasses is sitting at a desk with two monitors in front of her.
She is leaning slightly to one side, one hand on the mouse, the other hand
holding her chin as she looks at the screen — concentrating, evaluating
something. She wears a plain white short-sleeve t-shirt. Her hair is tucked
behind one ear on the side visible to camera. The desk area is in a bright
open office — California daylight floods in from large windows behind her,
the light catching the edge of her hair. A colleague is walking past in the
background, blurred, carrying something. She is in the center of the frame.
No text, timestamps, or UI overlays on the image.
```

### Person in conversation (teaching/discussion):
```
A still from a handheld video, slight grain, natural motion. Shot on Kodak
Portra 400 — shallow depth of field, fine grain. A man in his late 50s with
short grey-black hair and thin-framed rectangular glasses is sitting on the
edge of a desk at the front of a business school classroom, one leg hanging
off the desk. He wears a charcoal wool blazer over a grey crew-neck t-shirt,
sleeves pushed up slightly. He is leaning forward, one hand open mid-gesture
— he is in conversation with students. Three or four students sit at the
curved desk closest to him, some with laptops open, one leaning back in
their chair. The whiteboard behind him has writing on it. He is in the center
of the frame. No text, timestamps, or UI overlays on the image.
```

### Group photo (event/networking):
```
A photo taken at a business networking event. Three people standing together,
posing for the camera, smiling. The woman in the center is a young blonde
woman around 28 with small round gold wire-frame glasses. She has blonde hair
down past her shoulders, slightly wavy. She wears a dark navy blazer over a
plain white t-shirt. She is smiling naturally — not a big grin, a real smile,
eyes slightly squinted. The person on her left is a man in a grey suit,
taller, also smiling at camera. The person on her right is a woman in a dark
dress, holding a small clutch. They are standing close together the way
people do for a group photo — shoulders almost touching. Behind them: a
generic event venue space — other people mingling in the background, blurred.
The photo is taken straight-on by someone holding their phone at chest height
— the framing is slightly off-center, a bit too much space above their heads.
This is the kind of photo that ends up on LinkedIn the next morning. No text,
timestamps, or UI overlays on the image.
```

### Lounge discussion (multiple people, one focus):
```
The camera is at seated height, shooting across a lounge area. In the center
of the frame, a woman in her late 20s is sitting on a tan leather armchair.
She is leaning forward, legs crossed, one hand making a gesture at chest
height, mouth open — she is speaking. She has a short wavy bob at shoulder
length. She wears a navy short-sleeve knit top and small gold hoop earrings.
She is slim. To her left, a man sits on a matching leather sofa, his body
turned toward her — he wears a casual button-down shirt, visible from the
chest up. To her right, another person is seated on a second sofa, also
turned toward her — visible partially, cropped by the frame edge. The space
around them: a concrete pillar behind her, large potted plants — a tall
fiddle-leaf fig to the left, hanging greenery visible above. The floor has a
patterned area rug under the furniture. The ceiling is high with exposed
ducts and pendant lamps. Shot at high ISO — visible fine noise throughout,
slightly desaturated color. No text, timestamps, or UI overlays on the image.
```

---

## Anti-Patterns

| Don't | Why | Instead |
|-------|-----|---------|
| "A professional headshot of..." | Triggers portrait studio mode | Describe a moment, not a photo type |
| "Warm natural lighting" | Makes everything amber | Describe the space — model infers light |
| "Looking at each other" | Rigid staring | Describe body orientation only |
| Detailed poses for all people | Stiff arranged group | Focus one person, others in passing |
| "Back of someone's head in foreground" | Giant dark silhouette | Describe camera angle instead |
| "No wrinkles, clear skin" | Uncanny smooth face | Don't mention skin at all |
| "Chinese man", "Caucasian woman" | Triggers stereotypes | Describe hair color, features, clothing |
| Furniture/object inventory | Feels like a set design document | 3-5 specifics, then stop |
| "Relaxed", "confident", "professional" | AI stock photo mood | Describe what they're doing — mood is inferred |
| "Modern office" | Generic AI environment | Name specific materials and objects |

---

## Quality Check

Before outputting, verify:
- Is there ONE clear subject doing ONE specific action?
- Are other people mentioned briefly (one sentence or less)?
- Is the environment described with specific materials, not adjectives?
- Is there NO lighting instruction? NO mood adjective?
- Does it read like a storyboard frame description, not a creative brief?
- Would a real camera in this situation produce this image?
