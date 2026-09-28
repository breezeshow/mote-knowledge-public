---
title: Licensing
summary: 'How Mote licensing works: seats, admin, deployment, and SSO.'
type: narrative
domain: commercial
last-reviewed: 2026-08-05
review-interval: 180d
sources:
  - https://www.mote.com/pricing
---

# Licensing

How Mote licensing works at school and district scale.

## Deployment

Mote is delivered as a single Chrome extension; there is no per-device install
to manage. It deploys district-wide through the **Google Admin Console**, so
every student gets the Chrome Extension without IT having to touch a Chromebook
individually.

## Seats and roles

- A **district account has one owner**, and may have any number of admin
  accounts. Owner and admin accounts have identical access to analytics and
  admin settings.
- Each user is a **student** or a **teacher**; admins can change roles.
- Teachers see their own classes' usage data; admins see the institution-wide
  view (see [Mote Platform](../product/platform.md) and the
  [Impact Report](../product/platform.md)).
- District plans support **unlimited users** at no per-seat throttle.

## Adding users

Three ways:

- **Domain enablement:** any user with a matching email domain can join.
- **CSV upload:** bulk add by email list.
- **Individual email:** up to 20 at a time.

## Single sign-on

- **Google SSO** (recommended for Google Workspace schools)
- **ClassLink SSO**
- **Email** verification

## Pricing model

- **Individual:** flat annual subscription.
- **Multi-Seat (schools):** quote-based.

The canonical price points are in [pricing-facts.md](./pricing-facts.md); the
live source is [mote.com/pricing](https://www.mote.com/pricing).

## Related

- [plans.md](./plans.md): what each plan includes.
- [pricing-facts.md](./pricing-facts.md): the canonical price figures.
- [Mote Platform](../product/platform.md): the admin layer that runs licensing.
