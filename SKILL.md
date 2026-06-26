---
name: color-combo-skill
description: >-
  Curated named color palettes by mood and intent. Use when choosing colors
  for UI, branding, or visual design. Trigger on: "choose colors", "palette",
  "color scheme", "what colors should I use", "/color-combo-skill".
trigger_keywords:
  - color palette
  - color scheme
  - choose colors
  - what colors
  - palette for
  - /color-combo-skill
---

# Color Combo Skill

## Purpose
This skill teaches an agent to make better color decisions by providing curated, named color combos grouped by mood, style, and intent. When choosing colors for any visual output — UI, branding, content, or design — the agent should:

1. Identify the desired mood or context.
2. Match it to the appropriate category.
3. Pick a named combo that fits.
4. Use the color roles (Primary, Secondary, Accent, Supporting) consistently.
5. Check the contrast tier before applying Accent to text.

## Color Roles
- **Primary** — dominant background or base color.
- **Secondary** — supporting surface or text background.
- **Accent** — highlight, CTA, or attention-grabbing element.
- **Supporting** — subtle fill, border, divider, or shadow tones.

## Contrast Tiers
Every palette includes a contrast tier for its Accent-on-Primary pair:
- **UI-safe** — ≥4.5:1 contrast ratio. Safe for body text, labels, and interactive elements.
- **Large text only** — ≥3:1. Safe for headings (18px+ or 14px+ bold) only.
- **Decorative** — below 3:1. Never use for text. Use for borders, backgrounds, and visual accents only.

## Decision Guide
| Goal | Category to use |
|---|---|
| Premium, exclusive, editorial | Luxury |
| Aspirational, polished, budget-friendly | Luxury Facade |
| Calm, clean, editorial, soft brand | Luxury Facade > Soft Prestige |
| Futuristic, neon, surreal, cyber | Otherworldly |
| Disruptive, urban, bold, street-level | Acid Contemporary |
| Replacing a raw default color with a tasteful alternative | Refined Defaults |
| Soft background, calming gradient, wellness, airy UI | Soft Gradients |
| Organic, eco, botanical, outdoor, farm-to-table | Nature / Organic |
| Clean, structured, whitespace-first, mono | Minimalist |
| Artisan, coffee, wood, handmade, craft food | Rustic / Craft |
| Dark editorial, candles, alternative, perfume niche | Gothic / Dark Romance |
| Resort, cocktails, tropical, summer hospitality | Warm Tropical / Resort |
| Nostalgia, 70s/90s revival, vintage branding | Retro / Vintage |
| B2B SaaS, enterprise, regulated industries, serious mid-range | Corporate / Enterprise |
| Clinical, medical, health tech, patient-facing | Healthcare / Medical |
| Dark UI, performance, esports, gaming products | Gaming / Esports |

---

## Luxury
High-end, genuinely premium, opulent palettes. Use when the output must feel expensive, exclusive, and authoritative.

### Golden Obsession
- Style: Bold, opulent, high-impact luxury.
- Primary: #0B0B0F
- Secondary: #1C1A17
- Accent: #D4AF37
- Supporting: #B87333, #2D3138, #E9E1D0
- Contrast tier: **Large text only** (Accent #D4AF37 on Primary #0B0B0F — ~8.9:1 — UI-safe)
- Best for: Premium branding, fashion, luxury product visuals, dramatic editorial layouts.

### Arctic Prestige
- Style: Pure, crisp, controlled, refined luxury.
- Primary: #F5F8FA
- Secondary: #D6DEE6
- Accent: #9DB4C6
- Supporting: #5C7386, #1E2A39, #0B0F14
- Contrast tier: **Decorative** (Accent #9DB4C6 on Primary #F5F8FA — ~2.1:1 — decorative only)
- Best for: Minimal premium UI, cold-tech branding, high-trust interfaces, clean editorial design.

### Volcanic Intensity
- Style: Fierce, energetic, aggressive luxury.
- Primary: #0B0B0B
- Secondary: #1A1A1D
- Accent: #FF4D00
- Supporting: #8B1E00, #4A4746, #F2F1EE
- Contrast tier: **Large text only** (Accent #FF4D00 on Primary #0B0B0B — ~5.8:1 — UI-safe)
- Best for: Sports branding, performance themes, launch campaigns, bold visual identities.

### Futuristic Elegance
- Style: Sleek, cinematic, modern, premium-tech luxury.
- Primary: #F6F2E8
- Secondary: #C5C0C9
- Accent: #4B2E83
- Supporting: #0D1B2A, #FF7A00, #8FA7FF
- Contrast tier: **UI-safe** (Accent #4B2E83 on Primary #F6F2E8 — ~7.4:1)
- Best for: Luxury tech, innovation branding, futuristic interfaces, product storytelling.

### Emerald Dynasty
- Style: Regal, timeless, heritage-rich, ornate luxury.
- Primary: #0A5E4E
- Secondary: #093B33
- Accent: #D8C08A
- Supporting: #F2EDE1, #103F46, #071B1E
- Contrast tier: **UI-safe** (Accent #D8C08A on Primary #0A5E4E — ~5.2:1)
- Best for: Heritage brands, premium hospitality, jewel-tone identities, luxury packaging.

### Gradients

#### Obsidian Gold
- Saturated Stop: #1C1A17
- Light Stop: #D4AF37
- Style: Opulent, dramatic, deep-luxury.
- Best for: Hero sections on dark luxury sites, premium product cards, editorial headers.

#### Champagne Mist
- Saturated Stop: #C5C0C9
- Light Stop: #F6F2E8
- Style: Soft, sophisticated, cool luxury.
- Best for: Premium UI backgrounds, fashion editorial overlays, luxury SaaS hero sections.

#### Emerald Dusk
- Saturated Stop: #0A5E4E
- Light Stop: #D8C08A
- Style: Rich, jewel-tone, heritage warmth.
- Best for: Luxury hospitality hero sections, premium packaging mockup backgrounds.

---

## Luxury Facade
Aspirational, polished, premium-looking palettes for products or brands that need to appear more expensive, refined, or elevated than their price point suggests.

### Caramel Air
- Style: Soft, warm, approachable, upscale.
- Primary: #C07F45
- Secondary: #FCEDD6
- Accent: #97C6E0
- Contrast tier: **Decorative** (Accent #97C6E0 on Primary #C07F45 — ~1.8:1 — decorative only)
- Best for: Lifestyle branding, packaging, soft premium visuals, calm aspirational layouts.

### Moss Iris
- Style: Elegant, muted, artistic, boutique-like.
- Primary: #8F9D68
- Secondary: #FFF8EB
- Accent: #7A57CD
- Contrast tier: **Large text only** (Accent #7A57CD on Primary #8F9D68 — ~3.1:1)
- Best for: Boutique packaging, creative branding, elevated calm visuals, editorial accents.

### Citrus Royal
- Style: Bright, polished, clean, product-forward.
- Primary: #EF8E01
- Secondary: #0038BD
- Accent: #EEEEEE
- Contrast tier: **Large text only** (Accent #EEEEEE on Primary #EF8E01 — ~3.3:1)
- Best for: Consumer products, punchy premium-style branding, modern retail visuals.

### Skyline Poise
- Style: Cool, structured, calm, contemporary.
- Primary: #27262E
- Secondary: #E19C63
- Accent: #8BA5BE
- Contrast tier: **Large text only** (Accent #8BA5BE on Primary #27262E — ~4.1:1)
- Best for: Corporate branding, premium service design, modern calm interfaces.

### Indigo Minimal
- Style: Crisp, restrained, modern, airy.
- Primary: #F58F20
- Secondary: #04326D
- Accent: #B2BED6
- Contrast tier: **Decorative** (Accent #B2BED6 on Primary #F58F20 — ~1.9:1 — decorative only)
- Best for: Clean consumer branding, modern UI, balanced premium visuals.

### Coastal Contrast
- Style: Fresh, bright, accessible, polished.
- Primary: #95D9C0
- Secondary: #FFFFFF
- Accent: #D41F26
- Contrast tier: **Large text only** (Accent #D41F26 on Primary #95D9C0 — ~3.4:1)
- Best for: Lifestyle products, cheerful packaging, clean promotional graphics.

### Blue Horizon
- Style: Fresh, quiet, spacious, lightly premium.
- Primary: #F4FEFF
- Secondary: #A9C0E0
- Accent: #0E2F76
- Contrast tier: **UI-safe** (Accent #0E2F76 on Primary #F4FEFF — ~12.1:1)
- Best for: Calm UI, airy branding, wellness, minimal product design.

### Charcoal Citrus
- Style: Dark, energetic, expensive-looking, bold.
- Primary: #F58F20
- Secondary: #467434
- Accent: #363636
- Contrast tier: **Large text only** (Accent #363636 on Primary #F58F20 — ~4.0:1)
- Best for: Premium food, bold packaging, high-contrast aspirational branding.

### Soft Prestige
Calm, editorial, premium-looking palettes for clean brand systems.

#### Arctic Teal × Cloud Pearl
- Style: Clean, corporate, trustworthy.
- Primary: #0E7490
- Secondary: #F2F5F7
- Contrast tier: **UI-safe** (Primary #0E7490 on Secondary #F2F5F7 — ~5.3:1)
- Best for: Corporate branding, SaaS, trust-focused interfaces.

#### Terracotta Bloom × Sand Dune
- Style: Warm, earthy, editorial.
- Primary: #C96A4A
- Secondary: #EEDCC8
- Contrast tier: **Large text only** (Primary #C96A4A on Secondary #EEDCC8 — ~3.2:1)
- Best for: Lifestyle brands, warm packaging, editorial visuals.

#### Forest Moss × Vanilla Silk
- Style: Organic, natural, timeless.
- Primary: #4E6B45
- Secondary: #F4E8D0
- Contrast tier: **UI-safe** (Primary #4E6B45 on Secondary #F4E8D0 — ~5.8:1)
- Best for: Wellness, eco brands, natural products.

#### Indigo Night × Wisteria Glow
- Style: Modern, soft, premium.
- Primary: #2D4275
- Secondary: #D6C6F7
- Contrast tier: **UI-safe** (Primary #2D4275 on Secondary #D6C6F7 — ~6.1:1)
- Best for: Elegant UI, boutique branding, premium digital products.

### Gradients

#### Caramel Drift
- Saturated Stop: #C07F45
- Light Stop: #FCEDD6
- Style: Warm, soft, aspirational.
- Best for: Lifestyle landing page heroes, warm product card backgrounds.

#### Teal Pearl
- Saturated Stop: #0E7490
- Light Stop: #F2F5F7
- Style: Corporate calm, trustworthy, airy.
- Best for: SaaS hero gradients, clean service page backgrounds.

#### Wisteria Cloud
- Saturated Stop: #2D4275
- Light Stop: #D6C6F7
- Style: Soft, elegant, digital-premium.
- Best for: App onboarding screens, boutique brand hero sections.

---

## Otherworldly
Futuristic, neon, surreal, cyber, and reality-bending palettes. Use when the output must feel like it belongs to another dimension, a digital world, or a near-future aesthetic.

### Skin Tone
- Style: Warm, synthetic, soft sci-fi.
- Primary: #FFC6A8
- Secondary: #741A2F
- Accent: #FF0060
- Supporting: #A8003A, #FFE8D8, #2A0010
- Contrast tier: **Decorative** (Accent #FF0060 on Primary #FFC6A8 — ~2.2:1 — decorative only)
- Best for: Futuristic beauty, surreal fashion, human-centered sci-fi visuals.

### Vulcanico
- Style: Hot, aggressive, kinetic, ultra-digital.
- Primary: #FF4103
- Secondary: #001621
- Accent: #FFFFFF
- Supporting: #FF8040, #002A38, #FFD0A0
- Contrast tier: **UI-safe** (Accent #FFFFFF on Secondary #001621 — ~18.1:1 — use on dark surfaces)
- Best for: Cyberpunk branding, bold interface accents, intense visual identity.

### Silver Pulse
- Style: Minimal, electric, high-contrast, synthetic.
- Primary: #141414
- Secondary: #2BEE34
- Accent: #FFFFFF
- Supporting: #0A2A0A, #1A4A1A, #A0F0A0
- Contrast tier: **UI-safe** (Accent #FFFFFF on Primary #141414 — ~18.3:1)
- Best for: Neon UI, digital systems, futuristic dashboards.

### Turmeric Signal
- Style: Bright, sharp, experimental, energized.
- Primary: #FFBE0B
- Secondary: #2A2312
- Accent: #0A0A0A
- Supporting: #C88A00, #FFE880, #3A3018
- Contrast tier: **UI-safe** (Accent #0A0A0A on Primary #FFBE0B — ~14.8:1)
- Best for: Concept art, tech branding, attention-grabbing interfaces.

### Milky Grove
- Style: Soft, organic, luminous, slightly alien.
- Primary: #FFFDF1
- Secondary: #59C749
- Accent: #1A5A10
- Supporting: #A0E890, #D8F8D0, #0A3008
- Contrast tier: **UI-safe** (Accent #1A5A10 on Primary #FFFDF1 — ~9.3:1)
- Best for: Eco-futurism, wellness-tech, optimistic sci-fi visuals.

### Lime Oracle
- Style: Acidic, electric, strange, futuristic.
- Primary: #E4FD97
- Secondary: #2D3E2C
- Accent: #0A1A08
- Supporting: #B0D840, #4A6040, #F8FFD0
- Contrast tier: **UI-safe** (Accent #0A1A08 on Primary #E4FD97 — ~14.2:1)
- Best for: Experimental branding, cyber nature, bold futuristic systems.

### Cyprus Echo
- Style: Deep, calm, balanced, futuristic-natural.
- Primary: #004741
- Secondary: #F0EDE4
- Accent: #7FFFD4
- Supporting: #006858, #A0E8D8, #002820
- Contrast tier: **Large text only** (Accent #7FFFD4 on Primary #004741 — ~4.3:1)
- Best for: Premium eco-tech, serene interfaces, modern organic branding.

### True Signal
- Style: Hot, vivid, synthetic, pop-futurist.
- Primary: #FD1843
- Secondary: #FFF9FA
- Accent: #0A0A0A
- Supporting: #A80020, #FFB0C0, #FF6080
- Contrast tier: **UI-safe** (Accent #0A0A0A on Secondary #FFF9FA — ~19.4:1 — use on light surfaces)
- Best for: Youthful digital products, neon brand moments, sharp accent systems.

### Charcoal Violet
- Style: Dark, electric, surreal, high-contrast.
- Primary: #3C1A47
- Secondary: #B6FF00
- Accent: #F0F0F0
- Supporting: #6A2A80, #D0FF60, #1A0828
- Contrast tier: **UI-safe** (Accent #F0F0F0 on Primary #3C1A47 — ~9.8:1)
- Best for: Futuristic editorial design, bold app themes, neon contrast work.

### Gradients

#### Neon Abyss
- Saturated Stop: #3C1A47
- Light Stop: #B6FF00
- Style: Dark, electric, surreal. High voltage in a gradient form.
- Best for: Cyberpunk hero banners, dark app backgrounds, event site headers.

#### Solar Flare
- Saturated Stop: #FF4103
- Light Stop: #FFBE0B
- Style: Hot, kinetic, ultra-digital.
- Best for: Launch pages, aggressive tech campaigns, gaming UI backgrounds.

#### Void Pulse
- Saturated Stop: #141414
- Light Stop: #2BEE34
- Style: Dark synthetic, neon-on-black, terminal energy.
- Best for: Hacker aesthetic, dark dashboard backgrounds, digital underground hero sections.

---

## Acid Contemporary
Disruptive, urban, high-voltage palettes. These combos are confrontational by design — they belong to street culture, bold editorial, event branding, and any context where the visual needs to hit like a punch. No subtlety. No compromise.

### Ink Volt
- Style: Maximum contrast, street editorial, aggressive typographic energy.
- Primary: #0A0A0A
- Secondary: #F5E800
- Accent: #AAAAAA
- Supporting: #1A1A1A
- Contrast tier: **UI-safe** (Secondary #F5E800 on Primary #0A0A0A — ~18.1:1)
- Best for: Urban posters, music events, bold typographic campaigns, street brand launches.

### Crimson Grid
- Style: Dark tech, cinematic tension, high-drama red.
- Primary: #0D0D0D
- Secondary: #CC0A20
- Accent: #FFFFFF
- Supporting: #1A0A0A, #3A0010
- Contrast tier: **UI-safe** (Accent #FFFFFF on Primary #0D0D0D — ~19.2:1)
- Best for: Design conferences, dark editorial, film and event identity, tech brand moments.

### Blood Stage
- Style: Raw, mythic, performance-driven, crowd energy.
- Primary: #C8102E
- Secondary: #0A0A0A
- Accent: #FFFFFF
- Supporting: #8B0000, #5C0015
- Contrast tier: **UI-safe** (Accent #FFFFFF on Secondary #0A0A0A — ~19.6:1 — use on dark surfaces)
- Best for: Sports campaigns, concert and tour branding, action editorial, hero visuals.

### Tactical Lime
- Style: Military edge, athletic aggression, acid-nature contrast.
- Primary: #3B3D2A
- Secondary: #C2F03A
- Accent: #1A6B5C
- Supporting: #CC2B2B, #1A1A1A
- Contrast tier: **Large text only** (Accent #1A6B5C on Primary #3B3D2A — ~3.3:1)
- Best for: Sportswear, outdoor gear, performance culture, urban athletic branding.

### Void Green
- Style: Digital underground, hacker aesthetic, neon life in darkness.
- Primary: #050F05
- Secondary: #1AE81A
- Accent: #0D4A0D
- Supporting: #002200, #111111
- Contrast tier: **UI-safe** (Secondary #1AE81A on Primary #050F05 — ~14.6:1 — use Secondary for text)
- Best for: Tech events, music platforms, underground culture, digital activism visuals.

### Gradients

#### Volt Smear
- Saturated Stop: #0A0A0A
- Light Stop: #F5E800
- Style: Maximum contrast, street energy, aggressive.
- Best for: Event hero sections, music festival pages, bold typographic landing pages.

#### Crimson Fade
- Saturated Stop: #CC0A20
- Light Stop: #0D0D0D
- Style: Dark, cinematic, tension-loaded.
- Best for: Dark editorial hero sections, concert or film identity pages.

#### Acid Burn
- Saturated Stop: #3B3D2A
- Light Stop: #C2F03A
- Style: Military-organic, high contrast, athletic.
- Best for: Sportswear campaign backgrounds, gear product hero sections.

---

## Refined Defaults
Smarter, more nuanced alternatives to the blunt base colors that beginners and lazy tools default to. When a context calls for black, white, blue, red, green, or purple — never use the raw value. Use these instead.

> **Agent rule:** If you are about to use #000000, #ffffff, #0000ff, #ff0000, #00ff00, or #9a4dff — stop. Pick from the refined alternatives below instead.

### Instead of Black (#000000)
- Use: #161616, #232323, #2C2C2C, #363636
- Best for: Premium dark UI, tech product photography, headphones/audio brands, minimal dark packaging.
- Why: Pure black feels flat and printed. These near-blacks have warmth or coolness that reads more intentional.

### Instead of White (#ffffff)
- Use: #F6F6F6, #EEEEF0, #DEDEDE, #E1E1E1
- Best for: Product photography backdrops, minimal UI, skincare, wellness, clean SaaS interfaces.
- Why: Pure white glows on screen and feels sterile. Off-whites feel considered, premium, and easier on the eye.

### Instead of Blue (#0000ff)
- Use: #347AEA, #1E2FB0, #1E4BA3, #223068
- Best for: Tech brands, SaaS, fashion accessories, consumer goods, healthcare.
- Why: Pure blue is aggressive and dated. These variants carry authority without shouting.

### Instead of Red (#ff0000)
- Use: #F64547, #D7202D, #941020, #C92D31
- Best for: Beauty, premium food, fashion, packaging, bold brand identities.
- Why: Pure red is alarm-level intensity. These reds feel designed, not defaulted to.

### Instead of Green (#00ff42)
- Use: #91B96B, #5C985A, #56754B, #306C5F
- Best for: Wellness, skincare, eco brands, perfume, natural product lines.
- Why: Neon green screams synthetic. These greens feel grown, not coded.

### Instead of Purple (#9a4dff)
- Use: #361269, #6000D3, #7C44A5, #665090
- Best for: Premium consumer brands, chocolate/food, tech, beauty, gaming.
- Why: Default bright purple feels accidental. These have weight, identity, and recognisability.

---

## Soft Gradients
Named two-stop gradient pairs built for calm, breathable, emotionally gentle visuals. Use for backgrounds, hero sections, UI cards, app onboarding, wellness, and any context that needs to feel soothing rather than stimulating.

> **Agent rule:** Each gradient is defined by two stops — Light Stop and Saturated Stop. Apply as a linear or radial gradient. Direction is flexible; top-to-bottom and diagonal both work well.

### Eucalyptus Glow
- Saturated Stop: #A7C4A0
- Light Stop: #F4EFE6
- Style: Organic, calm, natural, grounded.
- Best for: Wellness brands, skincare, eco packaging, spa identity, natural product backgrounds.

### Pearl Mauve
- Saturated Stop: #D8BFD8
- Light Stop: #FDFCFB
- Style: Delicate, feminine, soft luxury, dreamy.
- Best for: Beauty, bridal, fragrance, soft editorial, premium lifestyle backgrounds.

### Ocean Breeze
- Saturated Stop: #7FCDFF
- Light Stop: #DFF7FF
- Style: Light, airy, fresh, open.
- Best for: Travel, wellness apps, clean UI backgrounds, summer campaigns, healthcare.

### Peach Champagne
- Saturated Stop: #FFD3B6
- Light Stop: #FFF7F0
- Style: Warm, soft, inviting, gentle.
- Best for: Food and beverage, lifestyle, warm UI, gentle brand onboarding, pastel editorial.

### Dreamy Periwinkle
- Saturated Stop: #B8C0FF
- Light Stop: #E7D8FF
- Style: Soft, romantic, modern, slightly surreal.
- Best for: Digital products, Gen-Z beauty, dreamy editorial, calm app interfaces, creative soft branding.

### Mint Lagoon
- Saturated Stop: #6DD5C4
- Light Stop: #DFF6F0
- Style: Cool, refreshing, serene, clean.
- Best for: Spa, wellness tech, beauty apps, clean UI surfaces, fresh product packaging.

---

## Nature / Organic
Palettes rooted in the living world — soil, bark, moss, stone, sky, water. Use when the output must feel grounded, honest, and connected to the natural environment. These are not soft wellness palettes — they have weight and earthiness.

### Forest Floor
- Style: Dense, shadowed, rich, deeply organic.
- Primary: #2C3A2A
- Secondary: #4A5E3A
- Accent: #A8C080
- Supporting: #7A6B52, #1E2A1A, #E8E0D0
- Contrast tier: **Large text only** (Accent #A8C080 on Primary #2C3A2A — ~4.2:1)
- Best for: Outdoor brands, forest retreat identity, eco-premium packaging, botanical editorial.

### River Stone
- Style: Cool, muted, mineral, grounded.
- Primary: #5A6B6E
- Secondary: #D4D8D0
- Accent: #3A8A78
- Supporting: #8A9A98, #2A3A3C, #F0EDE8
- Contrast tier: **Decorative** (Accent #3A8A78 on Primary #5A6B6E — ~1.6:1 — decorative only)
- Best for: Mineral water, stone-texture UI, spa identity, clean eco product design.

### Golden Meadow
- Style: Warm, open, harvest-light, pastoral.
- Primary: #C8A84B
- Secondary: #F5EDD0
- Accent: #6B8A3A
- Supporting: #A07840, #3A4A28, #FBF7EC
- Contrast tier: **Large text only** (Accent #6B8A3A on Primary #C8A84B — ~3.0:1)
- Best for: Farm-to-table brands, organic food, seed packaging, agrarian editorial.

### Bark & Sage
- Style: Rough, honest, textured, understated.
- Primary: #7A6248
- Secondary: #E8E0D0
- Accent: #7A9A68
- Supporting: #4A3A2C, #B0A888, #F5F0E8
- Contrast tier: **Decorative** (Accent #7A9A68 on Primary #7A6248 — ~1.5:1 — decorative only)
- Best for: Botanical skincare, herbal brands, outdoor lifestyle, natural home goods.

### Deep Canopy
- Style: Lush, tropical-dense, vivid organic.
- Primary: #1A3A2A
- Secondary: #2E5A3A
- Accent: #C8D84A
- Supporting: #4A7A50, #0E2018, #F0F0E0
- Contrast tier: **UI-safe** (Accent #C8D84A on Primary #1A3A2A — ~8.7:1)
- Best for: Rainforest brands, jungle editorial, premium botanical identity, eco luxury.

### Gradients

#### Morning Moss
- Saturated Stop: #4A5E3A
- Light Stop: #E8E0D0
- Style: Organic, earthy, grounded dawn.
- Best for: Eco brand hero sections, natural product landing pages, botanical app backgrounds.

#### Stone Wash
- Saturated Stop: #5A6B6E
- Light Stop: #F0EDE8
- Style: Cool mineral, muted, clean nature.
- Best for: Mineral skincare, spa UI backgrounds, nature-editorial hero sections.

#### Canopy Light
- Saturated Stop: #1A3A2A
- Light Stop: #C8D84A
- Style: Dense-to-vivid, lush, dramatic organic.
- Best for: Rainforest brand hero sections, eco-luxury backgrounds, botanical event pages.

---

## Minimalist
Palettes built on restraint. One dominant neutral, one precise accent, maximum whitespace. The discipline here is not about being boring — it's about being surgically intentional. Agents should use these when the design's job is to get out of the way.

> **Agent rule:** In Minimalist contexts, never add more than one accent color. If tempted to add a second accent, remove it. Whitespace is the second color.

### Bone & Carbon
- Style: Warm-neutral base, dark anchor, zero decoration.
- Primary: #F5F0EB
- Secondary: #1E1E1E
- Accent: #B07840
- Supporting: #D8D0C8, #3A3A3A
- Contrast tier: **Large text only** (Accent #B07840 on Primary #F5F0EB — ~3.8:1)
- Best for: Architecture portfolios, minimal luxury product pages, editorial photography sites.

### Chalk & Ink
- Style: Cool-white base, pure black type, clean.
- Primary: #F8F8F8
- Secondary: #111111
- Accent: #0057FF
- Supporting: #E0E0E0, #444444
- Contrast tier: **UI-safe** (Accent #0057FF on Primary #F8F8F8 — ~5.9:1)
- Best for: SaaS products, portfolio sites, digital agencies, clean documentation UI.

### Warm Mono
- Style: Single warm tone scaled across values, no contrast color.
- Primary: #FAF5EE
- Secondary: #D4C4A8
- Accent: #8A6A40
- Supporting: #B8A888, #5A4830
- Contrast tier: **Large text only** (Accent #8A6A40 on Primary #FAF5EE — ~4.0:1)
- Best for: Journal apps, reading interfaces, calm editorial, minimal lifestyle brands.

### Grey Scale Plus
- Style: Full greyscale with one surgical color pop.
- Primary: #F2F2F2
- Secondary: #2A2A2A
- Accent: #E8341C
- Supporting: #AAAAAA, #777777
- Contrast tier: **Large text only** (Accent #E8341C on Primary #F2F2F2 — ~4.0:1)
- Best for: Photography sites, modern agency pages, editorial with one hero color.

### Ash & Mist
- Style: Soft cool grey, barely-there, silent presence.
- Primary: #ECEEF0
- Secondary: #5A6270
- Accent: #3A7A8A
- Supporting: #B8C0C8, #2A3040
- Contrast tier: **UI-safe** (Accent #3A7A8A on Primary #ECEEF0 — ~4.8:1)
- Best for: Tech product sites, minimal SaaS, calm app UI, corporate minimalism.

### Gradients

#### Bone Fade
- Saturated Stop: #D8D0C8
- Light Stop: #F5F0EB
- Style: Barely-there, warm, invisible gradient.
- Best for: Minimal hero section backgrounds, architectural portfolio pages.

#### Ink Mist
- Saturated Stop: #2A2A2A
- Light Stop: #F8F8F8
- Style: Dark-to-light, clean, editorial.
- Best for: Scroll-reveal backgrounds, editorial section transitions, SaaS hero sections.

#### Ash Drift
- Saturated Stop: #5A6270
- Light Stop: #ECEEF0
- Style: Cool, quiet, corporate minimal.
- Best for: Tech product site backgrounds, calm app UI hero sections.

---

## Rustic / Craft
Palettes that smell like sawdust, coffee grounds, and beeswax. Warm amber, kraft paper, leather, raw linen, aged wood. Use these when the brand story is about hands, process, and authenticity — not polish.

### Amber Workshop
- Style: Warm, woody, handmade, artisan-rich.
- Primary: #8B5E3C
- Secondary: #F5E6CC
- Accent: #C8981A
- Supporting: #6A4228, #D4B890, #FAF3E0
- Contrast tier: **Large text only** (Accent #C8981A on Primary #8B5E3C — ~3.1:1)
- Best for: Coffee brands, woodworking, artisan food, craft brewery, handmade goods.

### Leather & Linen
- Style: Raw, tactile, warm restraint.
- Primary: #A0784A
- Secondary: #F0E8D8
- Accent: #5A3E28
- Supporting: #C8A878, #D8C8A8, #FAF6EE
- Contrast tier: **Large text only** (Accent #5A3E28 on Primary #A0784A — ~3.5:1)
- Best for: Artisan leather goods, heritage fashion accessories, handcraft studio identity.

### Smoked Oak
- Style: Dark, textured, aged, serious craft.
- Primary: #3A2A1E
- Secondary: #8A7060
- Accent: #C89050
- Supporting: #6A5040, #D8C0A0, #F5EEE0
- Contrast tier: **UI-safe** (Accent #C89050 on Primary #3A2A1E — ~5.6:1)
- Best for: Whiskey and spirits, aged cheese, serious artisan food, premium wood products.

### Kraft & Clay
- Style: Earthy, raw, unfinished, honest.
- Primary: #B8936A
- Secondary: #F5EDD8
- Accent: #7A5840
- Supporting: #D8B890, #A07850, #FBF5EA
- Contrast tier: **Decorative** (Accent #7A5840 on Primary #B8936A — ~2.3:1 — decorative only)
- Best for: Organic packaging, natural cosmetics, rustic bakery, handmade ceramics.

### Harvest Dusk
- Style: End-of-day warmth, rich amber sky, rural.
- Primary: #C07030
- Secondary: #F5D8A8
- Accent: #3A3020
- Supporting: #A05020, #E8C080, #FBF0D8
- Contrast tier: **UI-safe** (Accent #3A3020 on Primary #C07030 — ~5.1:1)
- Best for: Farm brands, harvest editorial, seasonal food campaigns, rustic event identity.

### Gradients

#### Amber Glow
- Saturated Stop: #8B5E3C
- Light Stop: #F5E6CC
- Style: Warm, woody, rich craft warmth.
- Best for: Coffee brand hero sections, artisan food landing pages, craft product backgrounds.

#### Smoked Drift
- Saturated Stop: #3A2A1E
- Light Stop: #C89050
- Style: Dark-to-amber, aged, serious.
- Best for: Whiskey brand hero sections, spirits product pages, dark rustic editorial.

#### Linen Haze
- Saturated Stop: #C8A878
- Light Stop: #FAF6EE
- Style: Raw, soft, tactile warmth.
- Best for: Artisan packaging mockup backgrounds, heritage brand hero sections.

---

## Gothic / Dark Romance
Palettes that live between candlelight and shadow. Deep wine, bone white, charcoal smoke, velvet purple, cold iron. Use when the output must feel dramatic, mysterious, and emotionally intense without becoming tacky or Halloween-adjacent.

> **Agent rule:** Gothic palettes must always include at least one near-white or bone tone as a contrast anchor. Pure black on pure black is a failure state.

### Velvet Crypt
- Style: Deep, opulent darkness, rich and suffocating.
- Primary: #1A0A1E
- Secondary: #3A1A40
- Accent: #C8A0E0
- Supporting: #7A4A90, #F0E8F8, #0E0610
- Contrast tier: **UI-safe** (Accent #C8A0E0 on Primary #1A0A1E — ~8.3:1)
- Best for: Dark luxury perfume, alternative fashion, gothic editorial, niche candle brands.

### Bone & Wine
- Style: Contrast-driven, romantic, decadent, timeless.
- Primary: #1A0808
- Secondary: #8B1A2A
- Accent: #F0E8D8
- Supporting: #5A0E18, #C8A090, #2A1010
- Contrast tier: **UI-safe** (Accent #F0E8D8 on Primary #1A0808 — ~14.6:1)
- Best for: Wine brands, dark romance editorial, gothic wedding, luxury candles, perfume identity.

### Iron Fog
- Style: Cold, industrial, melancholic, restrained gothic.
- Primary: #1E2028
- Secondary: #3A3E48
- Accent: #8A90A8
- Supporting: #5A5E70, #C8CAD0, #0E1018
- Contrast tier: **Large text only** (Accent #8A90A8 on Primary #1E2028 — ~4.1:1)
- Best for: Dark architectural photography, cold editorial, industrial brand identity, dark SaaS.

### Midnight Bloom
- Style: Floral, dark, mysterious, romantically lush.
- Primary: #1A1028
- Secondary: #4A2050
- Accent: #E050A0
- Supporting: #7A1850, #F8C8E0, #0E0818
- Contrast tier: **Large text only** (Accent #E050A0 on Primary #1A1028 — ~4.4:1)
- Best for: Dark beauty, gothic fashion, romantic editorial, alternative wedding brands.

### Ash Raven
- Style: Stripped, cold, mournful minimalism.
- Primary: #18181C
- Secondary: #2E2E34
- Accent: #E8E0D0
- Supporting: #4A4A52, #8A8A90, #F5F2EE
- Contrast tier: **UI-safe** (Accent #E8E0D0 on Primary #18181C — ~13.2:1)
- Best for: Dark portfolio sites, cinematic brand identity, cold editorial, minimal dark UI.

### Gradients

#### Velvet Smoke
- Saturated Stop: #1A0A1E
- Light Stop: #C8A0E0
- Style: Deep purple darkness to soft lavender, dramatic and opulent.
- Best for: Dark perfume hero sections, gothic brand backgrounds, alternative fashion pages.

#### Crimson Bone
- Saturated Stop: #8B1A2A
- Light Stop: #F0E8D8
- Style: Dark wine to warm bone, romantic and tense.
- Best for: Wine brand hero sections, dark romance editorial backgrounds, gothic candle pages.

#### Iron Veil
- Saturated Stop: #1E2028
- Light Stop: #C8CAD0
- Style: Cold dark to silver mist, industrial and melancholic.
- Best for: Dark architectural sites, cold editorial hero sections, industrial UI backgrounds.

---

## Warm Tropical / Resort
Palettes soaked in sun, salt water, and ripe fruit. Mango, coral, turquoise, warm sand, palm shadow. Use when the output must feel generous, joyful, and physically warm — like the first hour of a holiday.

### Mango Shore
- Style: Ripe, vivid, sun-drenched, joyful.
- Primary: #FF8C42
- Secondary: #FFF3E0
- Accent: #0097A7
- Supporting: #FF6B1A, #FFD580, #005F6B
- Contrast tier: **Large text only** (Accent #0097A7 on Primary #FF8C42 — ~3.1:1)
- Best for: Resort branding, tropical food and drink, summer campaigns, travel editorial.

### Coral Lagoon
- Style: Warm, aquatic, fresh, resort-luxe.
- Primary: #FF6F61
- Secondary: #FFF8F5
- Accent: #48CAE4
- Supporting: #E8504A, #A0D8E0, #FFC5B0
- Contrast tier: **Decorative** (Accent #48CAE4 on Primary #FF6F61 — ~1.9:1 — decorative only)
- Best for: Boutique hotel identity, beach bar branding, swimwear, holiday editorial.

### Palm & Sand
- Style: Calm, warm, natural resort, understated tropical.
- Primary: #E8C99A
- Secondary: #FBF5E8
- Accent: #3A7A6A
- Supporting: #B89870, #7AB090, #F5EDD8
- Contrast tier: **Large text only** (Accent #3A7A6A on Primary #E8C99A — ~3.7:1)
- Best for: Eco-resort identity, natural beach brand, calm travel UI, destination branding.

### Sunset Punch
- Style: Bold, saturated, cocktail-hour drama.
- Primary: #E84060
- Secondary: #FF9A3C
- Accent: #FFF0A0
- Supporting: #A01830, #FF6820, #FFC850
- Contrast tier: **Large text only** (Accent #FFF0A0 on Primary #E84060 — ~4.2:1)
- Best for: Cocktail brands, summer event identity, vivid tropical editorial, nightlife resort.

### Turquoise Drift
- Style: Cool tropical, sea glass, serene and open.
- Primary: #00B4C8
- Secondary: #E0F8FC
- Accent: #FF8040
- Supporting: #007A8A, #80D8E8, #FFF5EE
- Contrast tier: **Decorative** (Accent #FF8040 on Primary #00B4C8 — ~2.0:1 — decorative only)
- Best for: Diving brands, water sports, coastal wellness, clean tropical hospitality.

### Gradients

#### Mango Horizon
- Saturated Stop: #FF8C42
- Light Stop: #FFF3E0
- Style: Warm, ripe, sun-soaked.
- Best for: Resort landing page heroes, tropical product backgrounds, summer campaign sections.

#### Lagoon Fade
- Saturated Stop: #00B4C8
- Light Stop: #E0F8FC
- Style: Cool tropical, aquatic, serene.
- Best for: Coastal brand hero sections, travel UI backgrounds, sea-facing resort pages.

#### Sunset Wash
- Saturated Stop: #E84060
- Light Stop: #FF9A3C
- Style: Vivid, warm cocktail-hour drama.
- Best for: Cocktail brand hero sections, summer event pages, bold tropical editorial.

---

## Retro / Vintage
Palettes pulled from the past — faded, sun-bleached, tobacco-stained, and nostalgic. The key is controlled desaturation: these colors feel like they've been through time. Use when the brand story is about heritage, character, and cultural memory.

> **Agent rule:** Retro palettes must feel slightly faded. If a color looks too clean or saturated, pull it back. Vintage is about imperfection, not freshness.

### Mustard Record
- Style: 70s warmth, vinyl culture, bold and worn.
- Primary: #C8980A
- Secondary: #F5E8C0
- Accent: #A03820
- Supporting: #8A6808, #E0C870, #FAF0D8
- Contrast tier: **Large text only** (Accent #A03820 on Primary #C8980A — ~3.3:1)
- Best for: Music brands, vinyl culture, 70s-inspired editorial, retro food branding.

### Avocado Dream
- Style: Late-60s/70s organic, muted, period-correct.
- Primary: #7A8A38
- Secondary: #F0EDD8
- Accent: #C87840
- Supporting: #5A6828, #D8D0A8, #FAF5E8
- Contrast tier: **Decorative** (Accent #C87840 on Primary #7A8A38 — ~2.0:1 — decorative only)
- Best for: 70s revival branding, vintage kitchen goods, retro lifestyle editorial.

### Faded Denim
- Style: Washed, worn, American classic, 90s casual.
- Primary: #5A7090
- Secondary: #E8EEF5
- Accent: #C84830
- Supporting: #3A5070, #A8B8C8, #F5F0E8
- Contrast tier: **Large text only** (Accent #C84830 on Primary #5A7090 — ~3.6:1)
- Best for: Vintage clothing brands, Americana editorial, 90s nostalgia campaigns.

### Rust & Cream
- Style: Industrial vintage, aged metal, warm patina.
- Primary: #B84820
- Secondary: #F5EAD8
- Accent: #3A3828
- Supporting: #8A3818, #D8C0A0, #FAF5EC
- Contrast tier: **UI-safe** (Accent #3A3828 on Primary #B84820 — ~4.7:1)
- Best for: Heritage tool brands, aged industrial identity, vintage poster aesthetic, craft beer.

### Tobacco & Ivory
- Style: Aged paper, sepia warmth, old world editorial.
- Primary: #A08040
- Secondary: #F8F0DC
- Accent: #3A2E20
- Supporting: #7A6030, #D8C898, #FAF5E4
- Contrast tier: **UI-safe** (Accent #3A2E20 on Primary #A08040 — ~5.3:1)
- Best for: Vintage publishing, old-world brand identity, heritage whiskey, aged editorial.

### Gradients

#### Mustard Haze
- Saturated Stop: #C8980A
- Light Stop: #F5E8C0
- Style: Warm, faded, 70s glow.
- Best for: Retro music brand hero sections, vintage editorial backgrounds, 70s-themed pages.

#### Rust Fade
- Saturated Stop: #B84820
- Light Stop: #F5EAD8
- Style: Industrial, aged, warm patina.
- Best for: Heritage brand hero sections, vintage industrial editorial, craft beer pages.

#### Denim Wash
- Saturated Stop: #5A7090
- Light Stop: #E8EEF5
- Style: Washed, cool, nostalgic Americana.
- Best for: Vintage clothing brand backgrounds, 90s nostalgia campaign hero sections.

---

## Corporate / Enterprise
Palettes for serious, trust-driven, mid-to-large scale B2B contexts. These are not Luxury — they don't try to impress. They try to reassure. Structured, controlled, unambiguous. Use when the audience is a procurement team, a regulated industry, or a decision-maker who distrusts visual flair.

> **Agent rule:** Corporate palettes must always pass UI-safe contrast. Accessibility is non-negotiable in enterprise contexts.

### Steel Authority
- Style: Commanding, serious, institutional.
- Primary: #1A2540
- Secondary: #F0F4F8
- Accent: #2A7AE8
- Supporting: #2E3E58, #A8B8CC, #D8E4F0
- Contrast tier: **UI-safe** (Accent #2A7AE8 on Secondary #F0F4F8 — ~4.8:1)
- Best for: Enterprise SaaS, government-adjacent platforms, financial services, B2B product UI.

### Slate Trust
- Style: Calm, neutral, reliable, mid-weight authority.
- Primary: #F4F6F8
- Secondary: #2E3A4A
- Accent: #0A5C8A
- Supporting: #8A9AAA, #C8D4DC, #1A2A3A
- Contrast tier: **UI-safe** (Accent #0A5C8A on Primary #F4F6F8 — ~7.2:1)
- Best for: Corporate dashboards, internal tools, B2B marketing sites, SaaS admin interfaces.

### Navy Standard
- Style: Conservative, high-trust, classic corporate.
- Primary: #0A1E3C
- Secondary: #E8EEF5
- Accent: #C8A830
- Supporting: #1A3A5C, #A0B0C0, #F5F8FB
- Contrast tier: **UI-safe** (Accent #C8A830 on Primary #0A1E3C — ~7.8:1)
- Best for: Law firms, financial institutions, insurance, consulting firms, boardroom-facing design.

### Warm Corporate
- Style: Approachable authority, human-centered enterprise.
- Primary: #F8F5F0
- Secondary: #2A3040
- Accent: #C05A20
- Supporting: #D8CABB, #8A8A9A, #E8E0D8
- Contrast tier: **UI-safe** (Accent #C05A20 on Primary #F8F5F0 — ~5.4:1)
- Best for: HR platforms, people-ops tools, enterprise onboarding, workforce management UI.

### Gradients

#### Authority Fade
- Saturated Stop: #1A2540
- Light Stop: #F0F4F8
- Style: Dark navy to clean white, structured and trustworthy.
- Best for: Enterprise hero sections, B2B product site headers, corporate report covers.

#### Slate Wash
- Saturated Stop: #2E3A4A
- Light Stop: #F4F6F8
- Style: Calm, neutral, institutional.
- Best for: Corporate dashboard backgrounds, internal tool UI, B2B landing page sections.

---

## Healthcare / Medical
Palettes for clinical, patient-facing, and health-tech contexts. These must communicate safety, competence, and calm — simultaneously. They borrow from Minimalist restraint but carry additional meaning: every color choice here affects how much a user trusts the product with their health.

> **Agent rule:** Healthcare palettes must always pass UI-safe contrast. Never use red as a primary color in healthcare UI — it reads as emergency or error. Reserve red exclusively for alert and error states.

### Clinical Clarity
- Style: Clean, medical, precise, trustworthy.
- Primary: #F7FAFB
- Secondary: #1A4A6A
- Accent: #0A7A8A
- Supporting: #D0E8F0, #A0C4D8, #E8F4F8
- Contrast tier: **UI-safe** (Accent #0A7A8A on Primary #F7FAFB — ~5.8:1)
- Best for: Patient portals, telehealth apps, clinical dashboards, health record interfaces.

### Soft Triage
- Style: Warm, calm, reassuring, human-facing.
- Primary: #F8F6F0
- Secondary: #2A4A5A
- Accent: #1A7A5A
- Supporting: #C8D8CC, #A0B8B0, #E8F0EC
- Contrast tier: **UI-safe** (Accent #1A7A5A on Primary #F8F6F0 — ~5.6:1)
- Best for: Mental health apps, wellness platforms, patient communication tools, GP practice sites.

### Sterile Blue
- Style: Institutional, precise, hygienic, clinical authority.
- Primary: #EEF3F8
- Secondary: #0A3A5C
- Accent: #0057A8
- Supporting: #B8CCE0, #7A9AB8, #D8E8F4
- Contrast tier: **UI-safe** (Accent #0057A8 on Primary #EEF3F8 — ~7.1:1)
- Best for: Hospital systems, pharmaceutical branding, medical device UI, health insurance platforms.

### Vital Green
- Style: Life-affirming, fresh, health-positive, optimistic.
- Primary: #F0F8F0
- Secondary: #1A5A30
- Accent: #1A8A40
- Supporting: #A8D8B0, #D0EDD8, #C8E8C8
- Contrast tier: **UI-safe** (Accent #1A8A40 on Primary #F0F8F0 — ~6.4:1)
- Best for: Fitness apps, nutrition platforms, preventive health brands, pharmacy retail.

### Gradients

#### Clinical Mist
- Saturated Stop: #D0E8F0
- Light Stop: #F7FAFB
- Style: Barely-there, hygienic, clean.
- Best for: Patient portal hero sections, telehealth app backgrounds, health dashboard headers.

#### Vital Fade
- Saturated Stop: #A8D8B0
- Light Stop: #F0F8F0
- Style: Soft, life-affirming, health-positive.
- Best for: Wellness app onboarding, nutrition brand hero sections, fitness platform backgrounds.

---

## Gaming / Esports
Palettes for competitive, performance-driven, dark-UI gaming contexts. Distinct from Otherworldly — these are not surreal or editorial. They are about focus, aggression, and tribalism. Dark bases with high-voltage accents, built for screens viewed in dark rooms at high refresh rates.

> **Agent rule:** Gaming palettes are always dark-first. Never flip to a light primary unless explicitly building a casual/mobile gaming context. Neon accents must be used sparingly — one hero accent only.

### Midnight Frag
- Style: Dark, aggressive, competitive, high-focus.
- Primary: #0A0C10
- Secondary: #1A1E28
- Accent: #00E5FF
- Supporting: #2A3040, #006080, #A0F0FF
- Contrast tier: **UI-safe** (Accent #00E5FF on Primary #0A0C10 — ~14.8:1)
- Best for: FPS game UI, esports team identity, gaming peripheral branding, tournament platforms.

### Ember Clan
- Style: Fierce, tribal, warm aggression, fire energy.
- Primary: #100808
- Secondary: #1E1010
- Accent: #FF4800
- Supporting: #3A1000, #FF8840, #801800
- Contrast tier: **UI-safe** (Accent #FF4800 on Primary #100808 — ~9.2:1)
- Best for: Fighting game identity, team branding, esports org identity, gaming merch.

### Toxic Ranked
- Style: Neon-green aggression, hacker-sport, hyper-digital.
- Primary: #080C08
- Secondary: #101810
- Accent: #39FF14
- Supporting: #1A2E1A, #80C840, #003000
- Contrast tier: **UI-safe** (Accent #39FF14 on Primary #080C08 — ~15.6:1)
- Best for: Battle royale interfaces, speedrun culture, competitive ladder platforms, hacker-sport aesthetic.

### Chrome Arena
- Style: Metallic, cold, sci-fi competitive, premium esports.
- Primary: #0C0E14
- Secondary: #1E2230
- Accent: #C8D8FF
- Supporting: #2A3048, #6080C0, #8898C8
- Contrast tier: **UI-safe** (Accent #C8D8FF on Primary #0C0E14 — ~13.4:1)
- Best for: Premium esports platforms, game title screens, high-end gaming peripheral UI, team kits.

### Gradients

#### Frag Night
- Saturated Stop: #0A0C10
- Light Stop: #00E5FF
- Style: Black to electric cyan, ultra-competitive.
- Best for: Gaming platform hero sections, esports event headers, competitive UI backgrounds.

#### Ember Surge
- Saturated Stop: #100808
- Light Stop: #FF4800
- Style: Black to fire-orange, fierce and tribal.
- Best for: Fighting game brand hero sections, esports org identity pages, gaming merch backgrounds.

---

## CSS Usage

Reference snippets for how to emit these palettes in code. One pattern per context.

### Flat palette as CSS custom properties
```css
/* Golden Obsession — Luxury */
:root {
  --color-primary: #0B0B0F;
  --color-secondary: #1C1A17;
  --color-accent: #D4AF37;
  --color-supporting-1: #B87333;
  --color-supporting-2: #2D3138;
  --color-supporting-3: #E9E1D0;
}
```

### Gradient as CSS linear-gradient
```css
/* Obsidian Gold — Luxury gradient */
background: linear-gradient(135deg, #1C1A17 0%, #D4AF37 100%);

/* Velvet Smoke — Gothic / Dark Romance gradient */
background: linear-gradient(160deg, #1A0A1E 0%, #C8A0E0 100%);

/* Canopy Light — Nature / Organic gradient */
background: linear-gradient(135deg, #1A3A2A 0%, #C8D84A 100%);
```

### Gradient as CSS radial-gradient (for card/blob backgrounds)
```css
/* Dreamy Periwinkle — Soft Gradients */
background: radial-gradient(ellipse at top left, #E7D8FF 0%, #B8C0FF 100%);
```

### Dark palette with neon accent (Gaming pattern)
```css
/* Midnight Frag — Gaming / Esports */
:root {
  --color-bg: #0A0C10;
  --color-surface: #1A1E28;
  --color-accent: #00E5FF;
  --color-accent-dim: #006080;
  --color-text: #A0F0FF;
}

body { background: var(--color-bg); color: var(--color-text); }
.card { background: var(--color-surface); border: 1px solid var(--color-accent-dim); }
.cta  { background: var(--color-accent); color: var(--color-bg); }
```

### Healthcare accessible pattern
```css
/* Clinical Clarity — Healthcare / Medical */
:root {
  --color-bg: #F7FAFB;         /* UI-safe base */
  --color-surface: #D0E8F0;
  --color-primary-text: #1A4A6A;
  --color-action: #0A7A8A;     /* 5.8:1 on bg — UI-safe */
  --color-action-hover: #085A68;
}
/* Never use red as a primary color in healthcare UI */
```
