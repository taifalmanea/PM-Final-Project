# Roadmap, PRD & Prototype (Module 4)

## Your strategic anchors
- **Persona (M2), who are you solving for?:** A long-term, frequent StreamLine viewer who values discovering good content., wants to Find something genuinely worth watching quickly, without losing the evening to browsing., blocked by Overwhelmed by a 15,000-title catalog; after 20 minutes of scrolling, .
- **Primary success metric (M3), your leading indicator:** 30+ minute session rate — target a 20% relative increase, from 11% to 13.2%+.
- **Moment of misery (M2), the specific friction blocking the goal:** The user spends 20 minutes scrolling through the catalog, finds nothing they want, and closes StreamLine without watching anything.
- **Guardrail metric (M3), what must not drop or break:** Core Dispatch CSAT — currently 4.1/5 for Coordinators; it should not materially decline while the compliance workflow is improved.

## Scan the backlog & set a human baseline
- **My instinctive “quick wins” before touching the AI (2 to 3 feature IDs + why):** A1: A straightforward homepage experience that gives users curated recommendations without requiring a major new interaction.
A2: Directly addresses decision paralysis with a lightweight explanation layer on top of existing recommendations.
A3: Simple, visible UI change that can help users discover quality content without requiring a major change to the recommendation system.

## Audit, override & decide
- **Where did you override the AI? (feature + old vs. new score + why):** A3 – Hidden Gem Badge: Value 4 → 5. M3 data specifically identified high-quality, low-viewcount titles, which directly supports the discovery problem and gives this feature stronger evidence than a generic UI improvement.
- **Did the AI over-value a Sales/Eng request your M2 interviews don’t support?:** Yes, A8 Watch Party and A10 Offline Download. Both came from Sales and have weak connection to the M2 moment of misery, so I would deprioritize them despite their potential broader product value
- **Did it underweight something your M3 cohort/funnel data strongly supports?:** Yes, A3 Hidden Gem Badge. The M3 data identified the exact opportunity: high-quality content with low view counts. That is strong evidence for improving discovery and should raise A3’s Value to 5.

## Generate your interactive roadmap
- **My “Now” lane (this sprint), the 2 to 3 quick wins I’ll build first:** A1 – Spotlight Curated Rail, A2 – “Why You’ll Love This” Label, A3 – Hidden Gem Badge
- **What I cut, and the “no” I’m protecting the scope from:** Cut A6, A7, A8, and A10. I’m protecting the sprint from features that add engagement or convenience without directly solving the core problem: helping overwhelmed viewers find something worth watching quickly.
- **Prototype/roadmap screenshot link (paste into your deliverables):** # Feature Roadmap, Module 4 · StreamLine Spotlight

**Team:** 2 engineers + 1 designer

## Strategic anchors
- **Persona:** A long-term, frequent StreamLine viewer who values discovering good content., wants to Find something genuinely worth watching quickly, without losing the evening to browsing., blocked by Overwhelmed by a 15,000-title catalog; after 20 minutes of scrolling, .
- **Primary metric:** 30+ minute session rate — target a 20% relative increase, from 11% to 13.2%+.
- **Moment of misery:** The user spends 20 minutes scrolling through the catalog, finds nothing they want, and closes StreamLine without watching anything.
- **Guardrail:** Core Dispatch CSAT — currently 4.1/5 for Coordinators; it should not materially decline while the compliance workflow is improved.

## Scoring
| Feature | Value | Effort | Quadrant | Decision | Rationale |
|---|---|---|---|---|---|
| A1 Spotlight Curated Rail | 5 | 2 | Quick Win | Now | Directly tackles the 20-minute browsing misery by putting a focused set of worthwhile titles in front of the viewer immediately. |
| A2 'Why You'll Love This' Label | 5 | 2 | Quick Win | Now | Reduces decision paralysis by helping viewers quickly understand why a title is relevant to them. |
| A3 Hidden Gem Badge | 5 | 1 | Quick Win | Now | M3 data identifies high-quality, low-view titles, making this a low-effort way to improve discovery within the existing catalog. |
| A4 Mood-Based Entry Point | 3 | 3 | Time Sinker | Cut | Could reduce choice overload, but adds another decision point and is less directly validated than the core Spotlight concepts. |
| A5 Personalized Spotlight Queue | 5 | 5 | Major Project | Next | Highly aligned with the discovery problem, but building reliable taste-based personalization is too complex for a 3-week sprint. |
| A6 Spotlight Digest Email | 2 | 2 | Fill-In | Later | May drive re-engagement, but does not address the moment when an active viewer is already overwhelmed and abandoning the catalog. |
| A7 Curator Profiles | 2 | 3 | Time Sinker | Cut | Creates another discovery mechanism but introduces additional browsing rather than helping viewers choose quickly. |
| A8 Watch Party (Spotlight) | 1 | 5 | Time Sinker | Cut | Social viewing is disconnected from the core problem of finding something worth watching and is far too large for this sprint. |
| A9 Advanced Filter Engine | 3 | 4 | Time Sinker | Cut | Filters improve control but still require an overwhelmed viewer to search through a 15,000-title catalog. |
| A10 Offline Download (Spotlight) | 1 | 4 | Time Sinker | Cut | 	Only becomes useful after the viewer has already chosen something, so it does not solve the abandonment moment. |

## Roadmap
### NOW, 3-week sprint
- **A1 Spotlight Curated Rail**, Directly tackles the 20-minute browsing misery by putting a focused set of worthwhile titles in front of the viewer immediately.
- **A2 'Why You'll Love This' Label**, Reduces decision paralysis by helping viewers quickly understand why a title is relevant to them.
- **A3 Hidden Gem Badge**, M3 data identifies high-quality, low-view titles, making this a low-effort way to improve discovery within the existing catalog.

### NEXT, following 1-2 sprints
- **A5 Personalized Spotlight Queue**, Highly aligned with the discovery problem, but building reliable taste-based personalization is too complex for a 3-week sprint.

### LATER, backlog
- **A6 Spotlight Digest Email**, May drive re-engagement, but does not address the moment when an active viewer is already overwhelmed and abandoning the catalog.

### ✂ Cut List
- **A4 Mood-Based Entry Point**, Could reduce choice overload, but adds another decision point and is less directly validated than the core Spotlight concepts.
- **A7 Curator Profiles**, Creates another discovery mechanism but introduces additional browsing rather than helping viewers choose quickly.
- **A8 Watch Party (Spotlight)**, Social viewing is disconnected from the core problem of finding something worth watching and is far too large for this sprint.
- **A9 Advanced Filter Engine**, Filters improve control but still require an overwhelmed viewer to search through a 15,000-title catalog.
- **A10 Offline Download (Spotlight)**, Only becomes useful after the viewer has already chosen something, so it does not solve the abandonment moment.
