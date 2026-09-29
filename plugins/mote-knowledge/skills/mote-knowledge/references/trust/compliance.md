---
title: Compliance
summary: 'Mote''s regulatory compliance and certification posture: education-privacy law, infrastructure certifications, DPA, and jurisdiction notes.'
type: facts
domain: trust
last-reviewed: 2026-09-29
review-interval: 180d
sources:
  - https://www.mote.com/privacy
---

# Compliance

The regulatory and certification posture Mote stands behind. The authoritative
source is [mote.com/privacy](https://www.mote.com/privacy).

## What to surface (by surface type)

Different surfaces need different depth of compliance claims. Pick the
right set; never list everything in short-form copy.

| Surface | Default safe minimum | Add when relevant |
|---|---|---|
| **Short-form** (one-pager, email, social, sales follow-up, 250-400 word brief) | **FERPA, COPPA** | **GDPR** for European audiences; **Australian Privacy Act** for Australian audiences |
| **Long-form** (RFPs, district decks, security questionnaires) | FERPA, COPPA, GDPR, DPF | AWS hosting certifications (ISO 27001, SOC 2 Type 2, PCI DSS, FISMA; always stated as AWS's), SDPC, Student Privacy Pledge |
| **State-specific** (Maryland, Texas, California, etc.) | Default minimum + the relevant state statute | State Student Data Privacy Act if named |

**Rule of thumb**: COPPA and FERPA are *always* the headline. GDPR joins
them for European customers. Everything else is depth-on-request.

**Never assert a certification Mote doesn't actually hold.** When in doubt
on a specific claim, check this file's tables below.

## Education privacy & data protection

| Standard | Status |
|---|---|
| **FERPA** (US student privacy) | Compliant |
| **COPPA** (US child privacy, under 13) | Compliant |
| **GDPR** (EU data protection) | Compliant |
| **Australian Privacy Act** | Compliant |
| **EU-U.S. Data Privacy Framework (DPF)** | Certified participant |
| **UK Extension to the EU-U.S. DPF** | Signatory |
| **Student Data Privacy Consortium (SDPC)** | Member |
| **Student Privacy Pledge** | Signatory (since 2020) |

State-specific (US):

- **Maryland COMAR Title 13A** and the **Maryland Student Data Privacy Act:**
  compliant.

## Infrastructure certifications (via AWS)

Mote is hosted on Amazon Web Services, whose infrastructure is certified to
ISO 27001, SOC 2 Type 2, PCI DSS Level 1 and FISMA. These are AWS
certifications; AWS's SOC 2 report is available on request.

## Data Processing Agreement

A GDPR-compliant DPA template is available, referenced on mote.com/privacy for
UK schools and downloadable from there. For other jurisdictions Mote can work
with the institution to execute an appropriate DPA. Contact `support@mote.com`.

## Jurisdiction notes

- **Canada (PIPEDA / provincial laws):** data is stored in AWS US West (Oregon),
  not Canada. Risk is mitigated by DPF certification, encryption in transit and
  at rest, contractual protections, and student-specific safeguards; a DPA is
  available. No data is sold (relevant to Alberta's POPA).
- **EU / UK:** DPF-certified including the UK Extension; DPA template available;
  data is processed only when necessary for service delivery, operations,
  support, or with user consent.
- **Australia:** compliant with the Australian Privacy Act.

## Related

- [privacy.md](./privacy.md): what's collected, retention, rights.
- [security.md](./security.md): infrastructure and breach response.
- [sub-processors.md](./sub-processors.md): third parties Mote uses.
