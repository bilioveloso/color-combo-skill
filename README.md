# Color Combo Skill

![color-combo-skill banner](https://user-gen-media-assets.s3.amazonaws.com/gpt4o_images/de22b6a4-9317-454b-9ca6-3b05728b6357.png)

An agent-ready color palette system with 16 categories, WCAG contrast guidance, CSS-ready gradients, and brand archetype routing.

## Part of the modular design system

This skill works best as part of a chain. After choosing a palette here, load:

| Next need | Skill |
|---|---|
| Visual effects, glass, gradients, motion | [design-effects-skill](https://github.com/bilioveloso/design-effects-skill) |
| Typeface and font pairing | [font-pairing-skill](https://github.com/bilioveloso/font-pairing-skill) |
| Icon library and style | [icon-system-skill](https://github.com/bilioveloso/icon-system-skill) |

For a complete design brief, start at [design-mapper-skill](https://github.com/bilioveloso/design-mapper-skill) — it routes all four skills in the right order.

## Categories

| Category | Description |
|---|---|
| **Luxury** | Genuinely premium, opulent, high-end palettes |
| **Luxury Facade** | Aspirational palettes for products that need to look more expensive |
| **Luxury Facade › Soft Prestige** | Calm, editorial, clean brand palettes |
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
| **Seasonal** | Spring, Summer, Autumn, Winter campaign palettes |

## What each palette includes

- Named combo with evocative style description
- Primary, Secondary, Accent, Supporting hex codes
- WCAG contrast ratio (AA/AAA badge, or decorative-only warning)
- Best-for use cases
- CSS-ready `linear-gradient()` for every gradient pair
- Embedded agent rules per category

## How to use

Point your agent at `SKILL.md`. The agent will:

1. Consult the Decision Guide or Brand Archetype Guide to select a category.
2. Pick the named combo that fits the mood.
3. Apply colors using the defined roles: Primary, Secondary, Accent, Supporting.
4. Check the WCAG contrast note before using Accent on text.
5. Carry the palette forward to the next skill in the chain.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for submission format and rules.

## License

MIT — see [LICENSE](LICENSE).

## Maintained by

[@bilioveloso](https://github.com/bilioveloso)