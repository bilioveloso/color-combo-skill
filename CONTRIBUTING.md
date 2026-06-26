# Contributing to Color Combo Skill

Thanks for wanting to contribute. This skill is a curated resource for AI agents making color decisions — quality and consistency matter more than quantity.

## Before you start

Read the full [SKILL.md](./SKILL.md) carefully. Understand the existing categories, the color role system (Primary, Secondary, Accent, Supporting), and the naming conventions. Contributions that don't match the existing format will be asked to revise before merging.

## What we welcome

- **New named combos** added to an existing category
- **New gradient pairs** added to an existing category's Gradients section
- **New categories** — only if the aesthetic is genuinely distinct and not covered by existing categories
- **Corrections** — wrong hex codes, broken formatting, or naming inconsistencies

## What we don't accept

- Generic, untested color combos with no design rationale
- Duplicate moods already covered by existing combos
- Categories that overlap heavily with existing ones
- AI-generated palettes submitted without human curation and validation

## How to contribute

1. **Fork** this repository
2. **Create a branch** — name it descriptively, e.g. `add-neon-industrial-combo` or `fix-velvet-crypt-hex`
3. **Make your changes** following the format below exactly
4. **Open a Pull Request** with a clear title and a short description of what you added and why it belongs

## Format rules

Every combo must follow this structure precisely:

```
### Combo Name
- Style: Short adjective list describing the visual feeling.
- Primary: #XXXXXX
- Secondary: #XXXXXX
- Accent: #XXXXXX
- Supporting: #XXXXXX, #XXXXXX
- Best for: Specific use cases, not vague ones.
```

Every gradient must follow this structure:

```
#### Gradient Name
- Saturated Stop: #XXXXXX
- Light Stop: #XXXXXX
- Style: Short description.
- Best for: Specific use cases.
```

## Quality bar

Ask yourself before submitting:
- Would a professional designer use this combo without hesitation?
- Is the naming evocative and specific — not generic like "Blue Calm" or "Dark Mode"?
- Does it fill a real gap, or is it redundant with something already in the skill?
- Have you actually tested how it looks rendered, not just as hex values on a white background?

If the answer to any of these is uncertain, keep refining.

## Review process

All pull requests are reviewed by the maintainer. You may be asked to adjust colors, rename combos, or restructure your addition to fit the skill better. This is normal — treat it as a design review, not a rejection.

There is no guaranteed timeline for review. Be patient.
