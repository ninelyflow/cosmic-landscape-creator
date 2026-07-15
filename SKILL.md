---
name: cosmic-landscape-creator
description: >-
  Cosmic Landscape Creator — Midjourney Variable Prompt System.
  Generates thousands of unique cosmic landscape prompts by combining 5 variable categories
  (10 options each). When the user asks to create a cosmic landscape, space scene,
  nebula wallpaper, alien world, or says "cosmic", "space art", "nebula landscape",
  "generate a cosmic prompt" — use this skill. It picks options from Nebula Color,
  Mountain Type, Water Body, Atmosphere, and Art Style to compose a ready-to-use
  Midjourney /imagine prompt.
tags: [midjourney, prompt-engineering, cosmic, landscape, ai-art, image-generation, space]
---

# Cosmic Landscape Creator — Variable Prompt System

A Midjourney prompt template that generates **thousands of unique cosmic landscapes** by swapping variables across 5 categories. One master prompt, infinite worlds.

## Master Prompt

```
/imagine [NEBULA COLOR] nebula swirling over [MOUNTAIN TYPE] mountains with [WATER BODY] at [ATMOSPHERE], [ART STYLE], cosmic landscape --ar 16:9 --v 6
```

---

## Variable Library (10 options per category)

### 1. NEBULA COLOR
| # | Color | Effect |
|---|-------|--------|
| 1 | Golden Stardust | Warm, majestic, classic space art |
| 2 | Amethyst Dream | Purple/violet tones, mystical |
| 3 | Emerald Aurora | Green shimmer, rare and exotic |
| 4 | Crimson Veil | Deep red, dramatic and intense |
| 5 | Sapphire Cascade | Blue gradient, calm and cosmic |
| 6 | Rose Nebula | Soft pink, dreamy and romantic |
| 7 | Copper Storm | Orange/bronze, fiery energy |
| 8 | Silver Frost | White/blue metallic, icy elegance |
| 9 | Obsidian Glow | Dark with subtle purple highlights |
| 10 | Solar Flare | Yellow/orange burst, explosive energy |

### 2. MOUNTAIN TYPE
| # | Type | Description |
|---|------|-------------|
| 1 | Sandstone Arches | Smooth, eroded, warm-toned rock |
| 2 | Granite Peaks | Sharp, jagged, snow-capped |
| 3 | Volcanic Spires | Dark basalt, dramatic silhouettes |
| 4 | Crystal Cliffs | Translucent, glittering facets |
| 5 | Rolling Hills | Gentle, grassy, earth-toned |
| 6 | Floating Islands | Suspended rocks with waterfalls |
| 7 | Ice Glaciers | Blue-white, frozen, angular |
| 8 | Mesa Plateaus | Flat-topped, desert landscape |
| 9 | Obsidian Spikes | Black glass-like, sharp formations |
| 10 | Coral Formations | Organic, textured, ocean-carved |

### 3. WATER BODY
| # | Type | Description |
|---|------|-------------|
| 1 | Mirror Lake | Perfect reflection, glassy surface |
| 2 | Ocean Waves | Rolling surf, whitecaps |
| 3 | Glowing River | Bioluminescent, flowing light |
| 4 | Frozen Tundra | Ice sheets, snow-covered |
| 5 | Waterfall Cascade | Multi-tiered, misty spray |
| 6 | Hot Springs | Steaming, mineral-colored pools |
| 7 | Crystal Stream | Clear, shallow, pebble-bottomed |
| 8 | Rainbow Lagoon | Multi-colored, tropical waters |
| 9 | Deep Abyss | Dark, mysterious, depth gradient |
| 10 | Floating Dewdrops | Levitating water spheres |

### 4. ATMOSPHERE
| # | Type | Description |
|---|------|-------------|
| 1 | Twilight Glow | Post-sunset purple/orange gradient |
| 2 | Midnight Clear | Star-filled, deep blue sky |
| 3 | Sunrise Burst | Golden rays, warm morning light |
| 4 | Stellar Aurora | Dancing lights across the sky |
| 5 | Foggy Veil | Low-lying mist, mysterious mood |
| 6 | Storm Front | Dark clouds with lightning strikes |
| 7 | Dusty Haze | Warm desert sand suspended in air |
| 8 | Rainbow Arc | Full spectrum arching across scene |
| 9 | Double Sunset | Two suns on the horizon |
| 10 | Ringed Planet | Saturn-like rings in the sky |

### 5. ART STYLE
| # | Style | Description |
|---|-------|-------------|
| 1 | Photorealistic | Ultra-detailed, camera-like clarity |
| 2 | Oil Painting | Thick brushstrokes, textured canvas |
| 3 | Digital Matte | Smooth gradients, cinematic scope |
| 4 | Watercolor Wash | Soft edges, paper texture bleed |
| 5 | Ethereal Glow | Soft focus, light-emitting elements |
| 6 | Ink & Wash | Bold lines with color washes |
| 7 | Retro Sci-Fi | 1970s paperback cover aesthetic |
| 8 | Pixel Art | Blocky retro game resolution |
| 9 | Minimalist Flat | Clean shapes, limited color palette |
| 10 | Hyperdetailed | Every grain and star visible |

---

## How to Use This Skill

### Mode A: User specifies a vibe
When the user describes a mood (e.g. "calm", "epic", "mysterious", "warm", "cold"), pick 1 option from each category that matches, then output the completed prompt.

### Mode B: Random exploration
If the user just says "give me one" or "surprise me", randomly pick 1 from each category and output the completed prompt.

### Mode C: Partial input
If the user specifies some variables (e.g. "I want a purple nebula with waterfalls"), lock those in and fill the rest randomly or ask.

### Mode D: Batch generation
If the user wants multiple, generate up to 5 at a time, each with different combinations. Describe the vibe of each in one line.

### Output format
Always output the full `/imagine` prompt, followed by a one-line vibe description:

```
/imagine Golden Stardust nebula swirling over Sandstone Arches mountains with Mirror Lake at Twilight Glow, Photorealistic, cosmic landscape --ar 16:9 --v 6
→ Warm golds reflecting in glassy water, dramatic arches silhouetted against sunset sky
```

---

## Midjourney Parameters
- `--ar 16:9` — cinematic widescreen (use `--ar 1:1` for Instagram, `--ar 9:16` for phone wallpapers, `--ar 4:5` or `--ar 2:3` for prints)
- `--v 6` — latest Midjourney model
- `--s 250` — add stylize for more artistic interpretation
- `--iw 2` — when using an image reference
- `--no text, watermark, person` — for clean output

---

## Pro Tips
1. Use consistent nebula + atmosphere colors for a coherent series
2. Start with 1-2 variables fixed and randomize the rest for exploration
3. For wall art prints, try `--ar 4:5` or `--ar 2:3`
4. Mix hot nebula (magenta/gold) with cold mountains (snow peaks) for maximum contrast
5. Pair reflection water (Mirror Lake) with Stellar Aurora for double-sky effects

---

## Get the PDF Guides

This skill gives you the complete variable library and prompt engine. For the full tutorial with visual examples, composition rules, and advanced Midjourney parameter tuning (36-page PDF guide + 5 example images), grab it on Gumroad:

**→ https://ninelyflow.gumroad.com/l/udtpit**

---

*Cosmic Landscape Creator — Prompt Engineering Lab. 10^5 worlds, one prompt.*
