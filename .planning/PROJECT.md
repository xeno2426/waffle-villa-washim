# Customer Feedback System

## What This Is
A new feedback flow for The Waffle Villa, consisting of a dedicated `feedbacks.html` page where guests can leave reviews via a modal, and a "Guest Voices" section on `index.html` showcasing recent reviews.

## Core Value
Streamlining customer feedback securely entirely via client-side `localStorage`, providing social proof directly on the homepage without needing a backend server or database.

## Requirements

### Validated

- [ ] Single-page layout architecture (`index.html`) — existing
- [ ] Pure HTML/CSS/JS stack with no external dependencies — existing
- [ ] Design system loaded with CSS variables (dark luxury editorial) — existing

### Active

- [ ] REQ-01: Create `feedbacks.html` following the design system
- [ ] REQ-02: Implement "Leave Feedback" modal with name, interactive star rating, and text area
- [ ] REQ-03: Implement "Thank You" modal
- [ ] REQ-04: Persist reviews in `localStorage("wv_reviews")` and render them in a feedback grid
- [ ] REQ-05: Add Reviews section (`#reviews`) on `index.html` that pulls the 3 most recent reviews
- [ ] REQ-06: Update desktop and mobile navigation links to include `feedbacks.html`

### Out of Scope

- [Backend Database] — Project rules mandate zero external dependencies/build step, so `localStorage` is used.
- [Review Moderation] — Since reviews are strictly local to the user's browser, moderation is not required.

## Key Decisions

| Decision | Rationale | Outcome |
|----------|-----------|---------|
| Client-side persistence | Zero backend rule | — Pending |

---
*Last updated: 2026-03-30 after initialization*

## Evolution

This document evolves at phase transitions and milestone boundaries.

**After each phase transition** (via `/gsd-transition`):
1. Requirements invalidated? → Move to Out of Scope with reason
2. Requirements validated? → Move to Validated with phase reference
3. New requirements emerged? → Add to Active
4. Decisions to log? → Add to Key Decisions
5. "What This Is" still accurate? → Update if drifted

**After each milestone** (via `/gsd-complete-milestone`):
1. Full review of all sections
2. Core Value check — still the right priority?
3. Audit Out of Scope — reasons still valid?
4. Update Context with current state
