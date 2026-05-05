# The Evolution of Web Design — Digital Museum
**IS117 Final Project | Aarav | Spring 2026**

**Live Site:** [https://ac2928.github.io/is117-museum-project/](https://ac2928.github.io/is117-museum-project/)

---

## Museum Topic

This museum traces the evolution of web design from 1991 to the present — and into the future. The central argument is that web design shifted from being driven by **technical constraint** to being driven by **human experience**. The exhibit is structured as a guided chronological journey across four eras: the Early Web (1990s), Web 2.0 (2000s), Modern Design (2010–present), and the emerging Future.

---

## Design Style — Swiss International Typographic Style

The site uses **Swiss design** (International Typographic Style) as its visual foundation:

- **Typography:** Bebas Neue (display), IBM Plex Sans (body), DM Mono (labels/captions), DM Serif Display (italic accents)
- **Color:** A strict palette of off-white (`#F5F0E8`), near-black (`#0A0A0A`), and a single accent red (`#D62828`)
- **Grid:** Structured 80px grid lines in dark sections, consistent spacing rhythm throughout
- **Layout:** Clean columns, deliberate whitespace, no decorative clutter
- **Tone:** Precise, structured, authoritative — form follows function

Swiss design was chosen because it mirrors the subject matter: the history of web design is itself a story about imposing visual structure onto an unstructured medium.

---

## Brand Archetype — The Sage

The **Sage** archetype guides the emotional identity of the site:

- The tone is educational, measured, and trustworthy — like a museum curator
- Content is presented as curated knowledge, not entertainment
- The visitor is treated as an intelligent person seeking to understand something deeply
- Language is clear and direct, never sensational

The Sage archetype shapes vocabulary ("exhibit," "artifact," "guided journey"), the structured narrative flow, and the restrained visual presentation.

---

## Cialdini Principle — Authority

The **Authority** principle (Cialdini) is applied throughout:

- A direct quote from **Tim Berners-Lee** (inventor of the World Wide Web) anchors the top of the exhibit, immediately establishing credibility
- Each section includes a sourced historical milestone or key fact (specific dates, names, measurements)
- External links point to credible sources: Web Design Museum archive, Wikipedia, MDN Documentation
- The visual system itself conveys authority — structured, professional, consistent

Authority encourages visitors to trust the content and continue exploring, because the site presents itself as a reliable, expert source.

---

## AI Orchestration Process

AI was used as a structured workflow tool, not a one-shot generator:

| Stage | AI Role |
|-------|---------|
| Research | Used ChatGPT to identify key milestones, people, and turning points in web design history |
| Planning | Used AI to map the narrative arc and decide exhibit structure before writing a line of code |
| Content drafting | Used AI to draft section copy, then reviewed and refined for accuracy and tone |
| Design iteration | Used Claude to build and refine the HTML/CSS design system across multiple rounds |
| Critique | Used AI to identify weaknesses (thin Future section, missing Cialdini signals, generic images) |
| Improvement | Acted on AI critique to add key facts, Tim Berners-Lee quote, artifact captions, and Future cards |

**The AI did not author the project.** Every piece of output was reviewed, directed, and revised under human judgment.

---

## How the Site Was Built

### Sprint 001 — Layout Cleanup (Midterm → Final)
- Established Swiss design system with proper token variables
- Replaced generic styling with intentional typographic hierarchy
- All CSS and JS kept in a single self-contained index.html for simplicity

### Sprint 002 — Content & Authority
- Added Tim Berners-Lee quote as opening Authority signal
- Wrote historical key-fact callout boxes for each exhibit
- Added artifact captions to all images
- Expanded and structured the Future section (was nearly empty)

### Sprint 003 — Refinement & Polish
- Added scroll-reveal animations for exhibit sections
- Added timeline connector elements between eras
- Fixed all navigation to use smooth scroll with fixed-nav offset
- Ensured responsive layout across mobile and desktop

---

## File Structure

```
docs/
└── index.html          ← Main museum page (HTML, CSS, and JS all in one file)

project_management/
├── active/             ← Current sprint work
├── completed/          ← Finished sprints
│   ├── SPRINT_001_layout_cleanup.md
│   └── SPRINT_002_final_polish.md
└── plannng/            ← Planning documents

AGENTS.md               ← AI workflow documentation
README.md               ← This file
SPEC.md                 ← Project specification
```

---

## Sources

- Tim Berners-Lee quote — *Weaving the Web*, 1999
- Web Design Museum Archive — [webdesignmuseum.org](https://www.webdesignmuseum.org/)
- Ethan Marcotte, "Responsive Web Design" — A List Apart, 2010
- MDN Web Docs — Responsive Design reference
- Wikipedia — Web 2.0 overview