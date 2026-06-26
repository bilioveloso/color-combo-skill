# Color Combo Skill

An agent-ready skill for better color decisions.

## What this is

This repo contains a `SKILL.md` file that teaches an AI agent how to choose colors with taste. It provides curated, named color palettes grouped by category — each with color roles, mood descriptions, and usage guidance.

## Categories

| Category | Description |
|---|---|
| **Luxury** | Genuinely premium, opulent, high-end palettes |
| **Luxury Facade** | Aspirational, polished palettes for affordable products that need to look expensive |
| **Luxury Facade > Soft Prestige** | Calm, editorial, clean brand palettes |
| **Otherworldly** | Futuristic, neon, surreal, cyber palettes |

## How to use

Point your agent at `SKILL.md` as a skill or context file. The agent will:

1. Read the Decision Guide to match context to a category.
2. Pick the named combo that fits the mood.
3. Apply colors using the defined roles: Primary, Secondary, Accent, Supporting.

## Adding combos

Send new color combos to be added with a category suggestion. Each entry needs:
- Combo name
- Hex values
- Style description
- Best for note

## Maintained by
[@bilioveloso](https://github.com/bilioveloso)
