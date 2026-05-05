# SPEC.md — Project Specification
**Web Design Museum | IS117 Final Project**

---

## Project Summary

A museum-style single-page website that guides visitors through the history of web design, from 1991 to the present and into the future. The site is built as a curated digital exhibit — not a list of facts, but a structured narrative experience.

---

## Topic

**The Evolution of Web Design**

Central argument: Web design transformed from a practice driven by technical constraint into a discipline centered on human experience. This shift happened gradually across three decades and continues today.

---

## Audience

Students, designers, and curious visitors with general web literacy. No technical background assumed. The exhibit should be accessible to anyone interested in how the internet became what it is.

---

## Design Style

**Swiss International Typographic Style**

- Clean grid-based layout
- Strong typographic hierarchy
- Minimal color palette (off-white, near-black, single accent red)
- No decorative elements — every visual choice is functional
- Fonts: Bebas Neue (display), IBM Plex Sans (body), DM Mono (labels), DM Serif Display (quotes)

---

## Brand Archetype

**The Sage**

- Tone: Educational, measured, trustworthy
- Voice: Clear and direct, like a knowledgeable curator
- Goal: Help the visitor understand something deeply, not just consume content

---

## Cialdini Principle

**Authority**

- Tim Berners-Lee quote at top of exhibit
- Historical milestones with specific dates and names
- External links to credible sources
- Visual system conveys professionalism and reliability

---

## Exhibit Structure

| Section | ID | Content |
|---------|-----|---------|
| Hero | `#hero` | Title, subtitle, CTA |
| Authority Quote | `#authority` | Tim Berners-Lee quote |
| About | `#about` | Exhibit overview |
| Exhibit I | `#s1990` | Early Web, 1991–1999 |
| Exhibit II | `#s2000` | Web 2.0, 2000–2010 |
| Exhibit III | `#smodern` | Modern Design, 2010–present |
| Exhibit IV | `#future` | What comes next |
| Why It Matters | `#matters` | Closing argument |
| Footer | — | Credits and design notes |

---

## Technical Requirements

- Single HTML page (`docs/index.html`)
- Separate CSS (`docs/css/styles.css`)
- Separate JS (`docs/js/main.js`)
- Hosted on GitHub Pages from `docs/` folder
- Responsive at 900px breakpoint
- Smooth scroll navigation with fixed-nav offset
- Scroll-reveal animations on exhibit content

---

## Success Criteria

- [ ] Visitor can navigate all sections without confusion
- [ ] Design style is visually consistent throughout
- [ ] Authority principle is visible and credible
- [ ] Each exhibit contains a real historical fact or milestone
- [ ] Future section contains substantive content (not placeholder)
- [ ] Site works on mobile
- [ ] README documents all design and AI decisions
