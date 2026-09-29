---
title: Data Handling
summary: How Mote uses personal information (and pointedly does not) including the no-AI-training-on-student-data commitment.
type: facts
domain: trust
last-reviewed: 2026-09-29
review-interval: 180d
sources:
  - https://www.mote.com/privacy
---

# Data Handling

How Mote uses (and pointedly does not use) the personal information it
collects. The authoritative source is
[mote.com/privacy](https://www.mote.com/privacy).

## Mote's data philosophy

Mote's revenue comes **only from subscriptions**, with no advertising and no data
monetization. The position is plain: tools that serve students should not double
as instruments for collecting on them.

## What Mote uses personal information for

- Account management and authentication
- Delivery of the Mote educational service
- Storing and providing access to user-created content
- Product improvement through **aggregated, anonymised** usage analytics
- School-admin reporting on usage within their domain
- Service-related communications (account notifications)
- User-education bulletins, surveys, and company updates (**adults only**)
- Purchase processing (paying customers only)

## What Mote does *not* use it for

- **Advertising.**
- **Sale to third parties.**
- **Data matching or profiling.**
- **Training or evaluating AI models on student-generated content or
  interactions.**

That last commitment is explicit (as stated in Mote's RFP responses): *"Mote does not use
student-generated content or interactions to train or evaluate AI models. Mote's
revenue comes exclusively from subscriptions, not from data monetization or
advertising."*

Mote's AI surface is **bounded**: text-to-speech, speech-to-text, translation,
word prediction, writing review, and the picture-dictionary image generator each
perform a specific assistive task. None produces open-ended generated text from
student content.

## Student protections (under 18)

Students indicate their age at sign-in. For users under 18, Mote applies:

1. **Email and IP exclusion:** removed from third-party analytics sharing.
2. **No marketing:** students are excluded from marketing emails entirely.
3. **Annual content deletion:** user-generated content is automatically deleted
   on the one-year anniversary of creation (see [privacy.md](./privacy.md) for
   the broader retention rules).
4. **Feature restrictions:** certain features are restricted as age-appropriate.

## Integration context: what Mote does and does not access

Mote integrates with: Google Workspace for Education (Docs, Slides, Sheets,
Classroom, Gmail, Forms); Canvas LMS; the Chrome browser (extension); any
webpage; and iOS / iPad apps.

Mote does **not** access or store:

- Google Drive files beyond what a user explicitly interacts with through the
  extension.
- LMS gradebook or roster data beyond what is needed for the integration.
- Email content or calendar data.

## Related

- [privacy.md](./privacy.md): what's collected, retention, rights.
- [sub-processors.md](./sub-processors.md): third parties Mote uses.
