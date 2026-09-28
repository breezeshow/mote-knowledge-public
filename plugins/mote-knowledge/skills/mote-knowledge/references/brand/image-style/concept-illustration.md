---
title: Concept illustration
summary: Larger duotone illustrations for landing-page benefit grids, pillar-page solution cards, one-pagers, and concept-led surfaces. Same 2-tone construction as feature icons, but palette varies across Mote color families for visual variety.
type: facts
domain: brand/image-style
last-reviewed: 2026-06-01
review-interval: 180d
sources:
  - brand/visual-identity.md (shared 2-tone construction principle)
  - brand/image-style/feature-icon.md (sibling spec, smaller scale, mono Mote Purple)
  - brand/image-style/assets/benefit-illustration/ (canonical v3 reference set)
---

# Concept illustration

## Purpose

Larger duotone illustrations used where a feature icon is too small but a
full editorial illustration would be too much. Common surfaces:

- **Landing-page benefit grids**: 3-6 illustrations side-by-side
  accompanying short benefit copy.
- **Pillar-page solution cards**: 3-6 solution images per pillar.
- **One-pagers**: single illustration per benefit / outcome.
- **Use-case key features**: feature-level visuals on use-case pages.

Construction system is shared with feature icons (see
[`feature-icon.md`](./feature-icon.md)). What differs: **scale**, **palette
rule**, and **complexity**.

## Subject rules

Each illustration represents **one feature, benefit, or concept**, distilled
to a single recognizable object. The job is to anchor the benefit visually
alongside its text, not to tell a story.

- **One subject only.** Single object. No scenes.
- **Choose the most concrete object that names the benefit.** Read Aloud
  → headphones. Speech-to-Text → microphone. Highlight Notes → highlighter
  pen.
- **No people, no hands, no body parts.** Object only.
- **No background scene, no laptop as a "stage" for the object.** The
  object sits on a clean warm-white field.

## Composition

- **Square (1:1) at ~400-1000px** for grid use. Aspect ratio may vary per
  placement (see image-style index).
- **Centered subject** with generous padding around the object.
- **Negative space dominant**: the illustration breathes, not fills.

## Color palette

Each illustration is **2-tone within one Mote brand-color family**, same
construction as feature icons. Across **the set**, palette varies for visual
variety; there is **no semantic UDL mapping** in concept illustration (the
UDL color mapping applies to diagrams only; see `diagram.md`).

Per-illustration palette options:

- **Mote Purple family**: light purple fill `#F8E5FF` + Mote Purple stroke `#AC0AE8`.
- **Coral family**: light peach fill `#FFE5D6` + coral stroke `#F97316`.
- **Teal family**: light mint fill `#B8F2E5` + teal stroke `#14B8A6`.
- **Gold family**: light gold fill (from Figma) + gold stroke `#FBBF24`.

**Rule of thumb on a benefit grid:** vary the family across the set so it
doesn't all look monotone. Pick whichever family looks good with the
surrounding content; there's no fixed rule about which benefit gets which
color. Visual variety only.

## Style treatment

- **Always 2-tone within one family.** Light fill + darker stroke (identical
  construction to feature icons).
- **Flat and geometric.** No watercolour, no painterly wash, no shading, no
  gradients.
- **Consistent stroke weight** across the set, roughly 12-16% of the
  object's width. Rounded line caps and joins.
- **Optional secondary accent.** At this scale you can include *one* small
  accent per illustration in the same family, e.g. a faint sound-wave hint
  near headphones, a small ripple from a microphone, a stroke under a
  highlighter. **Single accent only**, never enough to read as a scene.

## Typography in image

None. Captions, headlines, and labels live in adjacent copy.

## Do / don't

**Do**

- A single pair of headphones in coral family for a Read Aloud benefit.
- A single microphone in teal family for a Speech-to-Text benefit.
- A single highlighter pen in purple family for a highlighting benefit.
- Vary color families across a benefit grid for visual variety.
- Optionally include one small secondary accent (single sound wave, single
  short stroke, single ripple).

**Don't**

- Include people, hands, or body parts.
- Add a laptop / Chromebook as a "stage" for the object.
- Use watercolour wash, painterly bloom, or gradients.
- Mix two color families inside one illustration.
- Include text or words inside the illustration.
- Render the object on a colored background; always use the warm-white field
  `#FFFBF7`.
- Try to tell a story with multiple objects, characters, or a scene.
- Use UDL color semantics; that's a diagram rule, not a concept-illustration rule.

## Reference images

The canonical concept-illustration set, generated 2026-06-01 from real
AT-for-Dyslexia landing-page benefits. Saved at
[`./assets/benefit-illustration/`](./assets/benefit-illustration/):

### Read Aloud (Coral family)

![Read Aloud concept illustration: headphones in coral family](./assets/benefit-illustration/benefit-coral-headphones.png)

### Speech-to-Text (Teal family)

![Speech-to-Text concept illustration: microphone in teal family](./assets/benefit-illustration/benefit-teal-microphone.png)

### Highlight Notes (Purple family)

![Highlight Notes concept illustration: highlighter in purple family](./assets/benefit-illustration/benefit-purple-highlighter.png)

Use this set as the visual anchor when generating any new concept
illustration. They define the canonical line weight, palette saturation,
composition density, and breathing room.

## AI prompt template

For Claude or another image-generation tool:

> A single **[OBJECT]**, three-quarter view, rendered as a clean 2-tone
> duotone illustration. Light fill in **[FAMILY-LIGHT HEX]** inside the
> object, confident stroke in **[FAMILY-PRIMARY HEX]** with consistent
> stroke weight. NO other colors, NO shading, NO gradients, NO scene, NO
> laptop, NO background scene, NO people, NO hands, NO body parts, NO text.
> Generously rounded corners. Centered on warm-white field `#FFFBF7` with
> generous negative space. Style: clean, friendly, modern, simple, like a
> Phosphor Duotone icon at larger illustration scale. Geometric and clean.
> Single object only. Optional: one small secondary accent in the same
> family (e.g. faint sound wave / small ripple / short stroke beneath).

**Variables:**

- `[OBJECT]`: the most concrete object naming the benefit.
- `[FAMILY-LIGHT HEX]` + `[FAMILY-PRIMARY HEX]`: pick a Mote family for
  visual variety across the page. Headline values:
  - **Mote Purple**: light `#F8E5FF`, primary `#AC0AE8`.
  - **Coral**: light `#FFE5D6`, primary `#F97316`.
  - **Teal**: light `#B8F2E5`, primary `#14B8A6`.
  - **Gold**: light (from Figma), primary `#FBBF24`.

**Iteration tips** (learned from the v1-v3 test runs):

- Add `single object only, no scene, no laptop` if the generator keeps
  framing the object inside a device or workspace.
- Add `NO people, NO hands, NO body parts` explicitly; the default tends
  to include a person doing the verb.
- Add `flat color fills, no watercolour, no painterly texture` if outputs
  drift painterly. Watercolour bloom was the first wrong instinct in v1
  and v2.
- The cleanest output is when the AI thinks of it as "icon at illustration
  scale", not "editorial illustration with one object."

**Iterate until** the illustration sits alongside the v3 reference set
above and reads as part of the same system.
