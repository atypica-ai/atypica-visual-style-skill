---
name: atypica-visual-style
description: Generate image prompts in atypica's visual language — either editorial abstraction (report/blog/podcast covers) or documentary realism (people, scenes, testimonials). Invoke this skill when asked to write an image prompt, create a cover, generate an avatar, or produce any visual asset for atypica.
argument-hint: "[description of what you need]"
---

# atypica Visual Style

Two visual modes that share the same DNA: all texture comes from real optics — a real camera, real light, real film stock. Never post-processing effects, never digital filters.

## Shared DNA

- **Film grain is physical** — it comes from ISO, film stock, sensor noise. Not a Photoshop overlay.
- **Blur is optical** — it comes from shallow depth of field, a real lens, distance to subject. Not gaussian blur.
- **Color is chemistry** — it comes from film emulsion (Portra 400, Kodak Gold), white balance, natural light. Not color grading sliders.
- **Texture is material** — frosted glass, linen, sandblasted metal, paper grain. Things you could touch.

The question is always: "What would a real camera capture in this situation?" — then describe that.

## Mode Selection

**Editorial Mode** — use when the image should be ABSTRACT. Covers for reports, blogs, podcasts, social sharing images. The subject is energy and mood, never literal illustration.

See: [editorial.md](editorial.md)

**Documentary Mode** — use when the image should show REAL PEOPLE in real scenes. Testimonial avatars, team photos, product screenshots with people, case study imagery.

See: [documentary.md](documentary.md)

## How to Choose

| The user wants... | Mode |
|---|---|
| Report/blog/podcast cover | Editorial |
| Social sharing image | Editorial |
| Abstract background | Editorial |
| Person portrait / avatar | Documentary |
| Team or workspace photo | Documentary |
| Product in use (with people) | Documentary |
| Event photo | Documentary |

## Output

Output one complete prompt in a fenced code block, ready to paste into Gemini or any image model. Precede with one sentence explaining the key choices made.
