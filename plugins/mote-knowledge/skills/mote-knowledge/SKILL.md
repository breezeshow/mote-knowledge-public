---
name: mote-knowledge
description: The single source of truth for what Mote is — company, product, features, brand voice, visual identity, market, pricing, and compliance. Use whenever a task involves writing, designing, auditing, or answering anything about Mote, or otherwise needs accurate Mote context.
---

# Mote Knowledge

This skill is Mote's structured knowledge base. Single source of truth for
what Mote is, how it sounds, how it positions, and how it looks. Load only
the leaf files the task actually needs (most tasks need 3-5, not all 80).

## What is Mote (essentials)

**Mote is the literacy platform for reading, writing, speaking, and listening**,
spanning the Mote Chrome Extension, Mote for iOS, Mote PDF, and the web. In K-12
procurement and RFP terms, it is an **assistive technology software platform** for
students with learning disabilities, reading and writing challenges, and English Learners,
deeply integrated with Chromebooks and Google Workspace.

**Six products carry the platform externally.** These are the products on the
website, and the naming below is canonical (matching the Webflow Products
collection). Lead with the Chrome Extension; mention Mote Translator only when
explicitly asked (active and supported, but not lead-with):

- **Mote Chrome Extension**: student tools for reading, writing, and creating,
  delivered as a Chrome extension, plus the Google Workspace integrations teachers
  use to make lessons accessible. The core product. The panel it opens is the
  **Mote Sidebar**, a current name subsidiary to the extension, not a second
  product.
- **Mote PDF**: Mote tools on any PDF, including OCR to accessibilize scanned
  files.
- **Mote for iOS**: Mote's native app for iPhone, iPad, and Mac.
- **Mote Vocab**: vocabulary and study activities. Customers see it labelled
  **My Vocab** in their dashboard.
- **Mote Writing Review**: spelling, homophone and grammar review that explains
  the rule instead of fixing it. A product in its own right because it lives in
  the app; also reachable as a button in the Chrome Extension.
- **Mote Translator** *(active, don't lead with)*: live spoken-lesson
  translation.

**One internal product** is real and supported but is not part of the website
product set. Do not list it alongside the six above in outward-facing copy:

- **Mote Platform**: the admin layer for schools and districts (accounts,
  rostering, Feature Access, Assessment Mode, analytics, Impact Report).

**Scale.** 25,000+ schools, 2 million+ users, 100+ countries.

**Founded** January 2020 by Will Jackson (CEO) and Alex Nunes (CTO). Mote
launched the Chrome extension that March, the same month US schools moved
to remote learning. Now a comprehensive K-12 assistive technology platform
sold mainly to districts.

**Positioning statement** (canonical; use verbatim in RFPs and external
press):

> *"Mote is an assistive technology software platform for K-12 students
> with learning disabilities, reading and writing challenges, and English Learners,
> deeply integrated with Chromebooks and Google Workspace. Unlike
> Read&Write, which is part of a broader cross-platform, multi-market
> portfolio, Mote is purpose-built for K-12 education, designed around the
> Mote Sidebar, which goes with students wherever they work on the web, and
> backed by an innovative team that ships product updates quickly based
> on what teachers actually ask for."*

## Global ALWAYS / NEVER rules

These apply to every Mote task. Domain-specific rules live in their
dedicated files.

### ALWAYS

- Capitalize **"Mote"** (never MOTE or mote).
- Use **en-US (American) spelling** throughout (color, organize, center,
  license, personalize), never en-GB (colour, organise, centre, licence,
  personalise).
- The core product is the **Mote Chrome Extension**. It opens the **Mote
  Sidebar**, the panel holding the student tools. Both names are current and they
  name different things: the extension is the product an admin deploys, the Mote
  Sidebar is the interface a student uses. Always write "Mote Sidebar" in full,
  never a bare "Sidebar" or "sidebar", and never call it a **toolbar** (that word
  is reserved for describing Read&Write). Never call the extension a "browser
  extension" or a "plugin". Mote as a whole is
  a **platform of products** (the Chrome Extension, Mote PDF, Mote for iOS, Mote
  Vocab, Mote Writing Review, Mote Translator) across Chrome, Apple devices, and
  the web, not a single extension.
- Capitalize feature names: Read Aloud, Text Prediction, Speech to Text,
  Screen Mask, Mote Writing Review, Mote PDF, Translation, Highlighter,
  Dictionary, Focus Mode.
- Use **25,000+ schools / 2 million+ users / 100+ countries** as the
  scale.
- Frame Mote tools as **universal in Tier 1, used more intensively at
  Tier 2 / Tier 3**: same tools across tiers, never accommodations
  *branded for* some students.
- Use **English Learners** as the primary term (first mention: *"English Learners (English
  Language Learners)"*; subsequent: *"English Learners"*).
- Be specific about compliance claims (e.g. *"TLS v1.2 or higher"*, not
  *"we use encryption"*).
- Lead with what the teacher or student can DO differently, not what was
  built.

### NEVER

- No **em-dashes** anywhere; they're an AI tell. Use commas, periods,
  semicolons, parens, or colons depending on context.
- No **emoji of any kind**, anywhere. No `✅`, `❌`, `⚠`, smileys, hearts.
  Use plain text labels in tables and lists.
- No **banned phrases**: *"We're excited"*, *"We're proud"*,
  *"Game-changer"*, *"Empower"* (as a verb for the product), *"Leverage"*
  (outside technical contexts), *"Seamless"*, *"Unlock the power of"*,
  *"Best-in-class"*, *"Transforms"* (use plain "changes"). Full list in
  `references/brand/voice-and-tone.md`.
- No **exclamation marks in the first sentence** of any copy.
- Never **proactively recommend or lead with Mote Translator**: an active
  product, describe only when explicitly asked.
- Never discuss **discontinued Mote products**.
- Never position Mote as a **"voice / audio / feedback company"**; the
  Chrome Extension is the product.
- Never **fabricate compliance claims**; only assert what Mote actually
  holds.
- Never claim Mote **replaces teachers**; it augments their work.
- Never use **fear-based messaging** about students falling behind.
- Never use **preachy accessibility messaging**; treat accessibility as
  foundational, not a selling point.

## The map: leaf files by domain

Load files as the task needs them. Most tasks load 3-5 leaf files, not
all of them.

### `references/brand/` (voice, positioning, identity)

| File | Load when |
|---|---|
| `voice-and-tone.md` | Writing or reviewing any Mote copy. Smart-colleague voice + full banned-phrase list. |
| `positioning.md` | Producing an RFP, sales deck, external press, or any outward-facing positioning copy. |
| `messaging-pillars.md` | Building a campaign, GTM piece, or major marketing narrative. The 5 pillars + audience matrix. |
| `terminology.md` | Any copy that needs terminology verification: capitalization, English Learner conventions, scale figures, Tier framing. |
| `visual-identity.md` | Producing any visual output. Color palette, typography, shadows, animations, logo. |
| `image-style/_index.md` | Producing an image. Routes to per-type specs (feature-icon, concept-illustration, human-photography, product-screenshot, diagram, logo-usage). Decision-history artifacts (moodboard files) live alongside but are not for ongoing use. |

### `references/company/`

| File | Load when |
|---|---|
| `mission-vision-values.md` | About-pages, internal alignment, RFP company sections. |
| `story.md` | Press releases, about-pages, company history. |
| `facts.md` | Boilerplate company facts (address, scale, Google for Education Partner status). |

### `references/product/`

| File | Load when |
|---|---|
| `overview.md` | Need the product suite at a glance. |
| `chrome-extension.md` | Anything about the core product. |
| `mote-pdf.md` | Anything about Mote on PDFs. |
| `mote-ios.md` | Anything about Mote for iOS (iPhone, iPad, Mac). |
| `translator.md` | Only when explicitly asked about Mote Translator. |
| `platform.md` | District admin, deployment, analytics (internal product). |
| `mote-vocab.md` | Vocabulary and study activities (Mote Vocab / My Vocab). |
| `writing-review.md` | Mote Writing Review, the product and the button. |
| `integrations.md` | Where Mote works (Chrome, Google, Canvas). |
| `onboarding-and-learning.md` | Getting-started questions. |
| `features/*.md` | Any specific feature (Read Aloud, Translation, Screen Mask, etc.). |

### `references/market/`

| File | Load when |
|---|---|
| `audiences.md` | Audience-specific copy (teacher, admin, IT, SpEd). |
| `problems.md` | The K-12 accessibility problem space. |
| `use-cases.md` | Common scenarios Mote solves. |

### `references/education/`

| File | Load when |
|---|---|
| `udl.md` | Anything UDL-framed. |
| `mtss.md` | Anything MTSS-framed (and the Tier-1 universal framing). |
| `standards.md` | RFP compliance with IDEA, Section 504, ESSA. |
| `why-it-matters.md` | The accessibility case at K-12. |

### `references/trust/`

| File | Load when |
|---|---|
| `privacy.md` | Student data, parent / district questions about privacy. |
| `security.md` | Encryption, infra, threat model. |
| `compliance.md` | FERPA, COPPA, GDPR, DPF: anything compliance-shaped. |
| `data-handling.md` | What Mote collects, where it goes. |
| `sub-processors.md` | AWS, Google Cloud, Deepgram, etc. |

### `references/commercial/`

| File | Load when |
|---|---|
| `plans.md` | Pricing-tier questions (free / individual / school / district). |
| `licensing.md` | Seats, admin, deployment licensing. |
| `pricing-facts.md` | Canonical figures for an RFP or quote. |

### `references/evidence/`

| File | Load when |
|---|---|
| `case-studies.md` | Real client stories. |
| `testimonials.md` | Attributable educator quotes. |
| `outcomes.md` | Research and outcome evidence. |
| `recognition.md` | Awards, recognition, press hits. |

## How to use this skill

1. **Identify the task domain.** Writing copy? Answering an RFP?
   Producing a visual? Describing a feature?
2. **Load only the leaf files the task actually needs.** Usually 3-5;
   never the whole tree.
3. **Check the ALWAYS / NEVER rules** above before generating any
   output.
4. **For specific terminology, voice, or positioning** questions, load
   the relevant `brand/` file.
5. **For images**, start at `brand/visual-identity.md` for the visual
   style stance, then route through `brand/image-style/_index.md` to
   the per-image-type file.

