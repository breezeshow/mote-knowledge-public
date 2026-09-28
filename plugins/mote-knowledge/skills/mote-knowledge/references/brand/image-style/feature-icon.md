---
title: Feature icons
summary: Small functional icons for benefit cards, feature lists, navigation, and course markers. Clean, geometric, two-tone in Mote Purple, consistent across the icon set as a brand marker. Varied palettes live in concept illustrations and diagrams, not here.
type: facts
domain: brand/image-style
last-reviewed: 2026-06-01
review-interval: 180d
sources:
  - brand/visual-identity.md (visual style stance, color palette)
  - assets/feature-icon-reference.png (canonical speech-bubble example)
---

# Feature icons

## Purpose

Small icons that mark a feature, benefit, or category. Appear in benefit
cards, feature lists, course thumbnails, navigation, and any context where a
single concept needs a quick visual marker. The most-reused image type on the
Mote site.

## Subject rules

Each icon represents **one feature or concept**, distilled to a single
recognizable object or shape. The job is to make the feature scannable, not
to illustrate it in detail.

- **One subject only.** One object, one shape, one symbol. No scenes.
- **Pick the most specific concrete object that names the feature.** Read
  Aloud → speaker. Highlighter → highlighter. Translation → speech-bubble
  pair. Screen Mask → focus reticle. Avoid abstract metaphors that need a
  caption to make sense.
- **No characters.** No faces, no people, no anthropomorphised objects (no
  laptops with smiles, no friendly cartoon pencils).

## Composition

- **72px square** to match the live `benefit-icon` component sizing.
- **Centered subject**, generous padding around the object. Don't fill edge to
  edge.
- **No depth on the icon itself.** No drop shadows, no inner glows, no
  realistic gradient. The only color variation is the duotone fill vs
  stroke (see Style treatment below).

## Color palette

**Feature icons are always Mote Purple.** Consistent across the whole icon
set. This is deliberate: feature icons act as a brand marker, and a uniform
Mote Purple icon system reinforces the brand wherever it appears.

The 2-tone treatment:

- **Stroke + internal accents**: Mote Purple `#AC0AE8`.
- **Fill**: Mote Purple Light `#F8E5FF`.

When the icon sits in the standard rounded 72px container, the container
uses the same Mote Purple light gradient (per the `benefit-icon-purple` CSS
class in the Style Guide PDF), so the whole composition stays in one family.

**No other color families for feature icons.** Coral, teal, and gold are
not used for feature icons. They live in:

- **Concept illustrations** ([`concept-illustration.md`](./concept-illustration.md)),
  where palette varies per illustration for visual variety.
- **Diagrams** (`diagram.md`), where UDL color mapping (Engagement = purple,
  Representation = coral, Action & Expression = teal) applies *here*, not
  to feature icons.

### Edge cases

- **Status icons** (success / warning / error / info) follow the Messaging
  color family (green / orange / red / blue; see `visual-identity.md`),
  not the feature-icon rule.
- **Course icons** may use varied colors per course; treat those as a
  separate icon system, not feature icons.

## Style treatment

- **Always 2-tone within one brand-color family.** Light fill (family's
  light end) + darker stroke (family's primary) + darker internal accents
  (dots, small shapes inside the symbol). See the reference image below.
- **Flat and geometric.** No 3D, no isometric, no realistic shading. No
  gradient on the symbol itself; the only color variation is fill vs
  stroke.
- **Consistent stroke weight across the icon set.** Roughly 12-16% of the
  icon's width (so a 72px icon takes a ~10-12px stroke). Rounded line caps
  and joins.
- **Generously rounded corners** on all shapes; matches Mote's soft-rounded
  visual language.
- **Functional, not decorative.** The icon should read clearly at 24px and
  at 72px.

## Typography in image

None. Feature icons carry no text. The feature name lives in the adjacent
label, never inside the icon.

## Do / don't

**Do**

- A two-tone speech bubble in Mote Purple (the canonical reference below).
- A speaker symbol for Read Aloud: light purple fill + Mote-Purple stroke.
- A highlighter shape, same Mote Purple treatment.
- Single subject, generous padding, rounded corners, consistent stroke
  weight.

**Don't**

- A monotone outlined icon with no fill (loses the Mote duotone look).
- A solid filled icon with no stroke contrast (flat, no depth).
- A coral / teal / gold feature icon. Feature icons are Mote Purple only.
  Varied palettes live in concept illustrations and diagrams, not here.
- A cartoon laptop with a smiling face.
- A scene of "students learning" inside the icon.
- 3D, isometric, or photorealistic styling.
- Text inside the icon.
- Generic AI-illustrative vector ("happy cloud", "fun pencil", etc.).

## Reference image

![Mote feature icon, a speech bubble in the canonical 2-tone style](./assets/feature-icon-reference.png)

The canonical Mote feature-icon style: a speech bubble in the Mote Purple
family. Note the **light purple fill**, **Mote-Purple stroke**, and
**Mote-Purple internal accents** (the three dots), generous rounded corners,
single subject centered with padding, no text, no background. Every new
feature icon should sit alongside this one and feel like part of the same
set.

## AI prompt template

For Claude or another image-generation tool:

> A flat, geometric **2-tone icon** of **[SUBJECT]**, rendered with a
> **light fill in `#F8E5FF` (Mote Purple Light)** and a **darker stroke
> plus darker internal accent details in `#AC0AE8` (Mote Purple)**. Stroke
> weight roughly 12-16% of the icon's width, rounded line caps and joins.
> Generously rounded corners on all shapes. Single subject, centered,
> generous padding around the object. No characters, no faces, no text, no
> background. Style: clean, modern, professional, friendly. Not cartoon.
> Not 3D. Not isometric. Not generic AI vector. Reference: the canonical
> Mote speech-bubble icon (light-purple fill, Mote-Purple stroke, three
> Mote-Purple dots inside).

**Variable:**

- `[SUBJECT]`: the most specific concrete object that names the feature.

**Iterate until** the icon reads cleanly at 24px (the size used in tight
feature lists) and looks at home alongside the reference speech-bubble icon
above.
