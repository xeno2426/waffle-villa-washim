# Roadmap

**5** phases | **11** requirements mapped | All v1 requirements covered ✓

| # | Phase | Goal | Requirements | Success Criteria |
|---|-------|------|--------------|------------------|
| 1 | `feedbacks.html` Base | Create core page layout and structure | PAGE-01, PAGE-02 | 2 |
| 2 | Feedback Modals | Implement form and interactions | MODL-01, MODL-02, MODL-03, MODL-04 | 3 |
| 3 | LocalStorage MVP | Save and display reviews | STOR-01, STOR-02 | 2 |
| 4 | Homepage Integration | Add Reviews section to index.html | INTG-01, INTG-02 | 2 |
| 5 | Navigation Updates | Link the new page across the site | INTG-03 | 2 |

### Phase Details

**Phase 1: `feedbacks.html` Base**
Goal: Create core page layout and structure
Requirements: PAGE-01, PAGE-02
Success criteria:
1. `feedbacks.html` exists and loads design system CSS.
2. Top Bar features a working back link to `index.html`.
**UI hint**: yes

**Phase 2: Feedback Modals**
Goal: Implement form and interactions
Requirements: MODL-01, MODL-02, MODL-03, MODL-04
Success criteria:
1. "Leave Feedback" button opens the form modal.
2. Clicking submit on empty fields shows shaking animation.
3. Submitting valid form closes feedback modal and opens Thank You modal.
**UI hint**: yes

**Phase 3: LocalStorage MVP**
Goal: Save and display reviews
Requirements: STOR-01, STOR-02
Success criteria:
1. Submitting a review adds it to `wv_reviews` in localStorage.
2. Feedback Grid renders all saved reviews on page load.

**Phase 4: Homepage Integration**
Goal: Add Reviews section to index.html
Requirements: INTG-01, INTG-02
Success criteria:
1. "GUEST VOICES" section appears before Contact.
2. Section displays up to 3 recent reviews or a placeholder if none exist.
**UI hint**: yes

**Phase 5: Navigation Updates**
Goal: Link the new page across the site
Requirements: INTG-03
Success criteria:
1. Mobile drawer contains a working "Feedback" link.
2. Footer contains a working "Feedback" link next to Games.
