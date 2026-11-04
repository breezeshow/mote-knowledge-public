---
title: Licensing
summary: 'How Mote licensing works: seats, admin, deployment, and SSO.'
type: narrative
domain: commercial
last-reviewed: 2026-11-04
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
individually. The extension ID is `ajphlblkfpppdpkgokiejbjfohfohhmk`.

There is no Chrome managed-policy configuration: admins control which tools are
on in **My School > Feature Access**, not through Chrome policy. Mote PDF is also
on the Google Workspace Marketplace and can be installed for the whole domain.

The interface comes in English, French, Spanish, Arabic and Mandarin Chinese.
Read Aloud and Translation cover 60+ languages.

**Not offered, so don't claim them:** an Android app, Clever rostering, a Safari
extension, Microsoft Edge (Mote doesn't work in Edge today).

## Seats and roles

- A **district account has one owner**, and may have any number of admin
  accounts. Owner and admin accounts have identical access to analytics and
  admin settings.
- Each user is a **student** or a **teacher**; admins can change roles.
- Teachers see their own classes' usage data; admins see the institution-wide
  view (see [Mote Platform](../product/platform.md) and the
  [Impact Report](../product/platform.md)).
- District pricing is **seat-based**: seats count staff and students, and admins
  see "{used} of {total} seats in use". **Classes** are unlimited on School and
  District plans; users are not.
- Minors can't be admins.
- When people the admin has added sign in, they join the subscription and get a
  license automatically.

## Adding users

Three ways:

- **Domain enablement:** any user with a matching email domain can join.
- **CSV upload:** bulk add by email list.
- **Individual email:** up to 20 at a time.

## Single sign-on

- **Google SSO** (recommended for Google Workspace schools)
- **ClassLink SSO** (and ClassLink rostering)
- **Sign in with Apple**
- **Email** verification

Mote does **not** support Clever, Microsoft / Entra, SAML or OneRoster.

## Pricing model

- **Unlimited (individual):** flat subscription, monthly or yearly, bought online.
- **Student or staff groups:** per seat on a sliding scale, bought online for 2
  to 100 seats.
- **School building:** a fixed price per building, by quote.
- **District or multi-site:** from $2,500 a year, by quote through sales. Never
  advertise the per-student rate.

The canonical price points are in [pricing-facts.md](./pricing-facts.md); the
live source is [mote.com/pricing](https://www.mote.com/pricing).

## Related

- [plans.md](./plans.md): what each plan includes.
- [pricing-facts.md](./pricing-facts.md): the canonical price figures.
- [Mote Platform](../product/platform.md): the admin layer that runs licensing.
