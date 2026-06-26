# Color Combo Skill

![color-combo-skill banner](https://user-gen-media-assets.s3.amazonaws.com/gpt4o_images/de22b6a4-9317-454b-9ca6-3b05728b6357.png)

An agent-ready skill for better color decisions.

## What this is

This repo contains a `SKILL.md` file that teaches an AI agent how to choose colors with taste. It provides curated, named color palettes grouped by category — each with color roles, mood descriptions, contrast tiers, and usage guidance.

## Categories

| Category | Description |
|---|---|
| **Luxury** | Genuinely premium, opulent, high-end palettes |
| **Luxury Facade** | Aspirational, polished palettes for affordable products that need to look expensive |
| **Luxury Facade > Soft Prestige** | Calm, editorial, clean brand palettes |
| **Otherworldly** | Futuristic, neon, surreal, cyber palettes |
| **Acid Contemporary** | Disruptive, urban, high-voltage palettes |
| **Refined Defaults** | Tasteful alternatives to raw default colors |
| **Soft Gradients** | Calm, breathable two-stop gradient pairs |
| **Nature / Organic** | Earthy, grounded, botanical palettes |
| **Minimalist** | Restrained, whitespace-first, one-accent palettes |
| **Rustic / Craft** | Artisan, warm amber, handmade palettes |
| **Gothic / Dark Romance** | Dramatic, mysterious, candlelit palettes |
| **Warm Tropical / Resort** | Sun-drenched, joyful, holiday palettes |
| **Retro / Vintage** | Faded, nostalgic, heritage palettes |
| **Corporate / Enterprise** | Trust-driven, structured, B2B palettes |
| **Healthcare / Medical** | Clinical, calm, patient-facing palettes |
| **Gaming / Esports** | Dark-first, neon-accented, competitive palettes |

## How to use

Point your agent at `SKILL.md` as a skill or context file. The agent will:

1. Read the Decision Guide to match context to a category.
2. Pick the named combo that fits the mood.
3. Apply colors using the defined roles: Primary, Secondary, Accent, Supporting.
4. Check the contrast tier before using Accent on text.

## Adding combos

Send new color combos to be added with a category suggestion. Each entry needs:
- Combo name
- Hex values
- Style description
- Best for note

## Maintained by
[@bilioveloso](https://github.com/bilioveloso)
