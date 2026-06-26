# Contributing to color-combo-skill

Contributions are welcome. All PRs are reviewed and merged by [@bilioveloso](https://github.com/bilioveloso).

## What you can contribute

- New named palettes within an existing category
- New category proposals (open an issue first)
- Corrections to hex codes or WCAG contrast ratios
- CSS gradient snippet fixes

## Submission format

Every new palette must include all of the following:

```
### Palette Name
- Style: [2-3 evocative words]
- Primary: #XXXXXX
- Secondary: #XXXXXX
- Accent: #XXXXXX
- Supporting: #XXXXXX, #XXXXXX
- Best for: [2-3 specific use cases]
- WCAG: Accent on Primary → X.X:1 ✅/⚠️ (AA/AAA / decorative only)
```

And if you include a gradient:

```
### Gradient Name
- Saturated Stop: #XXXXXX → Light Stop: #XXXXXX
```css
background: linear-gradient(135deg, #XXXXXX 0%, #XXXXXX 100%);
` ` `
```

## Rules

- All hex values must be verified (no approximate values)
- WCAG contrast ratio must be calculated, not estimated — use [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/)
- Palette names must be evocative and unique within the category
- Style descriptions: 2–3 words, no full sentences
- Do not submit palettes that are near-duplicates of existing ones

## Process

1. Fork the repo
2. Add your palette to the correct category in `SKILL.md`
3. Open a PR with the title format: `feat([Category]): Add [Palette Name]`
4. Wait for review — @bilioveloso will approve or request changes