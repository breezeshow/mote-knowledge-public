---
title: Image style (index)
summary: Mote's image guidance, organized by visual style rather than purpose. Six style files cover almost everything Mote produces; placements consume styles.
last-reviewed: 2026-06-01
review-interval: 180d
---

# Image style

Mote's image guidance is organized **by style**, not by placement. Each style
file describes the visual treatment durably; placements (hero, blog header,
social card, etc.) *consume* a style + a size rule.

The **visual style stance** that anchors all of these lives in
[`../visual-identity.md`](../visual-identity.md). Read that first before
generating any image.

## Cross-cutting rules

These apply to every image type, every channel.

- **Alt text every time.** Every image in the CMS, on the site, in social, in
  email, in slides (every one) needs descriptive alt text. The CMS already
  has dedicated alt-text fields; fill them.
- **Brand colors only.** No off-palette accents. Stick to the families in
  [`../visual-identity.md`](../visual-identity.md).
- **No characters, no cartoon faces in illustration.** Use real photography
  for people; use clean geometric duotone for icons and concept
  illustrations. Avoid the default "AI illustrative" trap (happy laptops with
  smiles, anthropomorphised pencils, friendly cartoon students).
- **Specificity beats vibe.** The image should name the concept, not gesture
  at it. *"The image IS the verb."* Depict the action, not the idea around
  it.
- **Honest framing.** No fake or generated screenshots of Mote's UI. Use real
  product captures.

## Style files

| File | Style | Palette rule | Common placements |
|---|---|---|---|
| [feature-icon.md](./feature-icon.md) | 2-tone duotone, small scale (~24-72px) | **Always Mote Purple**, consistent across the icon set as a brand marker | Benefit cards, feature lists, navigation, course markers |
| [concept-illustration.md](./concept-illustration.md) | 2-tone duotone, large scale (~400-1000px) | **Varies per illustration** across Mote families (purple / coral / teal / gold) for visual variety | Landing-page benefit grids, pillar-page solution cards, one-pagers, use-case key features |
| `human-photography.md` *(TBD)* | Documentary-feel photography of real people, real classrooms | n/a (real-world color) | Human heroes, case-study photos, lifestyle marketing |
| `product-screenshot.md` *(TBD)* | Mote UI captures on staged backgrounds (blob, drop shadow, optional frame device) | Background uses Mote color families | Product heroes, in-blog product references, pillar-page product callouts |
| `diagram.md` *(TBD)* | Clear K-12 expert diagrams in Mote colors | **UDL color mapping applies here**: Engagement = purple, Representation = coral, Action & Expression = teal | UDL / MTSS / framework diagrams in blog posts, pillar pages, slide decks |
| `logo-usage.md` *(TBD)* | Mote lockup placement rules | n/a | Anywhere the logo appears |

## Placements

Placement-specific rules (sizing, aspect ratio, layout) consume one of the
style files above. Common placements and the style they typically use:

| Placement | Style consumed | Typical size / aspect |
|---|---|---|
| Landing-page hero (human) | `human-photography.md` | 16:9 |
| Landing-page hero (product) | `product-screenshot.md` | 16:9 |
| Landing-page benefit grid (3-6 images) | `concept-illustration.md` | 1:1 |
| Benefit card icon (within content) | `feature-icon.md` | 72×72 |
| Pillar-page hero | `human-photography.md` or `product-screenshot.md` | 16:9 |
| Pillar-page solution cards (3-6) | `concept-illustration.md` | 1:1 |
| Blog post hero | `human-photography.md` (most) or `concept-illustration.md` (concept-led posts) | 16:9 |
| Case study hero | `human-photography.md` | 16:9 |
| Course thumbnail | mixed (typically `concept-illustration.md` for the icon + `human-photography.md` for surrounding marketing) | 16:9 + 1:1 |
| Social / OG card | `human-photography.md` or `product-screenshot.md` | 1200×630 (OG) |
| What's New | typically a GIF of Mote UI (`product-screenshot.md` flavour, animated) | 16:9 |
| Headshot / educator portrait | `human-photography.md` | 1:1 typically |
| Competitor comparison | `product-screenshot.md` for side-by-side UI, `concept-illustration.md` for conceptual differences | varies |

## How to use this folder

1. Start at [`../visual-identity.md`](../visual-identity.md) for the visual
   style stance, color palette, and typography.
2. Apply the cross-cutting rules above to *every* image.
3. Identify the placement in the **Placements** table.
4. Open the **style file** the placement consumes.
5. For AI generation, lift the AI prompt template from the style file and
   fill in the variables.
