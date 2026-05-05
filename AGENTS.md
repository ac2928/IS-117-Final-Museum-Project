# AGENTS.md — AI Orchestration Documentation
**Web Design Museum | IS117 Final Project**

This document describes how AI tools were used throughout the project. The goal was to use AI as a structured workflow partner, not a passive generator.

---

## AI Tools Used

- **ChatGPT (GPT-4)** — Research, content outlining, first-draft copy
- **Claude (Anthropic)** — HTML/CSS generation, design refinement, critique and improvement loops
- **Gemini** — Secondary research verification, image prompt generation

---

## Workflow by Stage

### Stage 1: Research
**Tool:** ChatGPT  
**Prompt approach:** Asked for major milestones in web design history, key people, turning points by decade. Cross-referenced against known sources.  
**Human role:** Selected which milestones were most important for the exhibit narrative. Discarded vague or generic outputs.

### Stage 2: Narrative Planning
**Tool:** ChatGPT  
**Prompt approach:** Asked AI to help structure a four-exhibit arc that tells a coherent story rather than listing facts.  
**Human role:** Decided the central argument ("technical constraint → human experience") and the exhibit order.

### Stage 3: Content Drafting
**Tool:** ChatGPT + Claude  
**Prompt approach:** Drafted section copy for each exhibit, then asked Claude to refine tone to match the Sage archetype — clear, measured, educational.  
**Human role:** Reviewed every paragraph. Replaced vague phrasing. Added specific dates and names for Authority signals.

### Stage 4: Design System Build
**Tool:** Claude  
**Prompt approach:** Described Swiss design requirements (token system, font choices, color palette, grid logic). Iterated across multiple rounds.  
**Human role:** Directed every visual decision. Rejected outputs that were too generic. Pushed for more typographic hierarchy and intentional whitespace.

### Stage 5: Critique Loop
**Tool:** Claude  
**Prompt approach:** Asked Claude to critique the site against the assignment rubric — what was weak, what was missing, what looked generic.  
**Human role:** Acted on the critique. Added Tim Berners-Lee quote (Authority), expanded Future section, added artifact captions, fixed nav scroll behavior.

### Stage 6: Final Polish
**Tool:** Claude  
**Prompt approach:** Asked for scroll-reveal animations, timeline connectors, and mobile responsiveness.  
**Human role:** Reviewed final output, tested in browser, made final edits to copy and layout.

---

## Key Principle

AI generated options. The human made decisions.

Every piece of AI output was reviewed before being accepted. The structured sprint process — research first, plan second, build third, critique fourth — meant AI was always working toward a clear human-defined goal rather than generating freely.

---

## What AI Cannot Replace

- The decision about *what story to tell*
- The judgment about *what looks right*
- The editorial choice of *what to cut*
- The understanding of *why the design choices matter*

These remained human throughout.
