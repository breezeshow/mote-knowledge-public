---
title: Mote Platform
summary: 'Mote''s admin layer for schools and districts: accounts, classes, logins, feature controls, and usage reporting.'
type: facts
domain: product
last-reviewed: 2026-11-04
review-interval: 180d
---

# Mote Platform

**Description.** Mote Platform is the administrative layer that lets schools,
districts, and colleges run Mote at scale: setting up accounts, managing classes,
controlling which features are available, and reporting on usage. It covers:

- **Security & compliance.** Mote meets FERPA, COPPA, and GDPR requirements,
  including the EU-U.S. Data Privacy Framework and its UK Extension. **Mote Privacy
  Controls** let an organization restrict Mote content so it stays within the school
  or district.
- **Class management.** Teachers create classes from the **My Classes** dashboard,
  enroll students through **Google Classroom** (the main way in; the roster keeps
  syncing), a join link, a 6-letter class code, or a QR code. A class takes up to
  **40 students**. Class limits per teacher: Free or trial **1**, Unlimited **5**,
  School and District plans **no limit**, and use
  the **Class Dashboard** to see student-level usage (Read Aloud minutes, Motes
  created, translations made). **Teacher Feature Controls** enable or disable Chrome Extension
  features for a whole class or an individual student, and **Assessment Mode**
  restricts features for a set length of time, keeping some tools available, or
  disabling them all, while a class sits an assessment. The teacher chooses the
  duration (30 minutes, 1 hour, 2 hours, 4 hours, or until the end of the school
  day), chooses which
  features to pause, and chooses who it applies to: the whole class, **or everyone
  except the students whose IEP requires Mote**, so a required accommodation is not
  withdrawn to run an assessment.
  **Co-teachers:** an adult who joins a class (by the same class link students
  use) shows on the roster as a **co-teacher**. Co-teachers do **not** receive the
  class trial, and Teacher Feature Controls do not apply to them: their feature
  access comes from their own Mote plan or license. (Motes created is a real
  Class Dashboard metric; see terminology.md for why copy avoids promoting it.)
- **Admin experience.** Account owners manage their institution from the **My
  School** dashboard. Users can be added by **domain enablement** (any matching
  email can join), **CSV upload**, or **individual email** (up to 20 at a time).
  **Feature Access** is an account-level control, found under My School, that sets
  a feature for every student in the school rather than class by class. Each feature
  has **three states**: **On**, **Off for all**, and **Off by default**. The last
  leaves the decision with the teacher rather than taking it away (they turn it on
  through Teacher Feature Controls). When a feature is unavailable, students are
  told why, and teachers can see which admin set it. **School
  Language** sets the default product locale for the whole school or district, so,
  for example, a Quebec board can set French and every student and teacher gets
  French by default; any individual can override it in their own personal settings.
  Mote's interface is **fully translated into French, Spanish, Arabic and Mandarin
  Chinese**: the Chrome Extension, the dashboard, and every button, label and prompt in
  between. (Distinct from Read Aloud and Translation, which cover 60+ languages of
  *content*; this is the product's own interface.)
  My School has four areas: **Manage Users**, **Analytics**, **Feature Access** and
  **School Language**. **Analytics** shows active students, Listening Minutes,
  translations, feature use, usage contexts and a translation breakdown, with the
  top 1,000 users and a CSV export. The **Usage Report** is a CSV with one row per
  user covering up to 365 days, sent as an emailed link valid for 24 hours. The
  **Impact Report** is a custom-generated report, in a UDL or MTSS framework, that
  crunches usage data and identifies areas of strength and opportunity across the
  whole institution. Domain options include "Student unlimited" and "All users
  Unlimited". An account has one owner and any number of admins; minors can't be
  admins.
- **Login options and rostering.** Users sign in with **Google SSO**, **ClassLink
  SSO**, **Sign in with Apple**, or **email** verification (Google SSO is recommended for the best Google
  Workspace experience). Mote honors **ClassLink rostering**, and classes can be
  imported from Google Classroom to map students to their teachers. Mote does
  **not** support Clever, Microsoft / Entra, SAML or OneRoster; never claim them.
- **Deployment.** IT force-installs the Chrome Extension for everyone from the
  Google Admin console (extension ID `ajphlblkfpppdpkgokiejbjfohfohhmk`). There is
  no Chrome managed-policy configuration; tools are controlled in Feature Access.
  Admins add people first (by domain, CSV or email); when those people sign in,
  they join the subscription and get a license automatically.
- **Data rights.** Personal data is hard-deleted on request; users can delete their
  own account, and admins can remove users. Mote estimates whether a user is a
  minor (admins can override it); minors can't be admins or use Mote Translator.
- **Content Library:** a central dashboard where a user's Mote recordings are
  stored, organized, and monitored; it is opened by **My Content** in the Chrome Extension.

**The controls line.** Wherever copy says every student gets the same tools, the
same page says who decides: *"Admins and teachers decide which tools are on for the
whole school, a class, or one student."* (or, speaking to the reader, *"You
decide..."*). Feature Access sets each tool for the whole school, Teacher Feature
Controls set it for a class or a student, and Assessment Mode can pause tools
during a test while keeping them on for students whose IEP requires them.

## Mote for Assessments

For locked-down exams, Mote points to **Mote for Assessments**: a separate kiosk
Chrome app for a dedicated Chromebook, with only Read Aloud, Speech to Text and
Text Prediction. Don't claim the Mote Chrome Extension works in lockdown browsers
other than Google Forms Locked Mode.

**How to use it.** Class management happens at the **My Classes** dashboard
(`mote.com/my-classes`); institution-level administration happens at the **My
School** dashboard (`mote.com/my-school`), available to account owners and
administrators. These are the logged-in product pages where the work is actually
done.
