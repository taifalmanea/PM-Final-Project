# Experimentation Plan (Module 5)

## Get your documents ready
- **From M3, your hypothesis sentence:** Based on qualitative evidence of Coordinators relying on manual workarounds and quantitative evidence showing that only 48% reach Compliance Checks, with the task taking 14.6 minutes versus a 3-minute benchmark and receiving 2.2/5 CSAT, I believe that simplifying the Compliance workflow for Coordinators will increase digital workflow completion and reduce manual workarounds. I will target at least a 20% relative increase in Compliance Check completion, while protecting Core Dispatch CSAT, and will make a go/no-go decision after 4–6 weeks of post-launch data.
- **From M3, your primary success metric & guardrail metric:** Compliance Check completion rate, increasing from the current 48% by at least 20% relative (to ~58%). & Core Dispatch CSAT — currently 4.1/5 for Coordinators; it should not materially decline while the compliance workflow is improved.
- **From M4, the feature you scoped in your PRD this is what you're testing:** Hidden Gem Badge

## Define your experiment parameters
- **Feature under test pull from your M4 PRD:** Hidden Gem Badge
- **Persona pull your M2 persona:** For my persona, A long-term, frequent viewer who values discovering good content but is overwhelmed by StreamLine’s large catalog. (goal: Find something genuinely worth watching quickly without spending a large part of the evening browsing.), identify the specific external tools or manual processes they use to bypass their friction: After 20 minutes of scrolling, they still cannot find anything they want to watch and close StreamLine, sometimes turning to an alternative like a DVD instead.
- **Expected outcome the behaviour change you expect, from your M3 hypothesis:** More Coordinators complete the digital workflow instead of relying on manual workarounds, reducing wasted time and improving account satisfaction, which should support retention and reduce churn risk.
- **Primary success metric the one number that defines success, from M3:** Compliance Check completion rate, increasing from the current 48% by at least 20% relative (to ~58%).
- **Baseline rate today's rate of your primary metric, from your M3 data:** Current Compliance Check completion rate 48%
- **Guardrail metric & boundary what must not break, and how far it can move before you investigate:** Average viewer satisfaction must not decrease by more than 5%, and the early playback exit rate must not increase by more than 5% relative to the baseline. Investigate if either threshold is exceeded.
- **Minimum Detectable Effect (MDE) the smallest improvement worth shipping, your floor:** A 10% relative increase in the percentage of viewers reaching a 30+ minute viewing session compared with the baseline.
- **Sample size per arm use the calculator in the builder, baseline + MDE:** 1,703
- **Traffic split & test duration 50/50 standard · cover ≥ 2 weekly cycles:** 14 days
- **Significance threshold p < 0.05 is standard, explain any deviation:** 5% (α = 0.05)

## Define your control and variant
- **Control (A) the current experience, reference your M2 moment of misery and M3 funnel/workflow data:** The user enters the catalog and spends around 20 minutes scrolling without finding something compelling to watch, then leaves without starting a meaningful viewing session. Today, only 11% of homepage visitors reach a 30+ minute session, while the share of users who search and then play has fallen from 41% to 34%.
- **Variant (B) your single change, copy the relevant screens & functional requirements from your M4 PRD:** The Home experience adds a “Hidden Gem” badge to qualifying title tiles. The badge is visible without interaction on the Spotlight Curated Rail and genre rows. On the title detail sheet, badged titles also show “Hidden Gem” and “Highly rated, rarely watched.”
- **Isolation check, what has NOT changed? list everything identical between arms (app version, recommendation engine, notifications, onboarding). If something changed inadvertently, your test is compromised.:** Everything remains identical between Control (A) and Variant (B), except for the addition of the Hidden Gem badge and its fixed explainer.

App version and platform
Catalog and title data
Recommendation engine
Home layout and existing content rows
Spotlight Curated Rail
Search and browsing functionality
Onboarding and user flow
Notifications and messaging
Title ratings and metadata
Playback experience
Pricing/subscription experience
Analytics and tracking
Eligibility and audience
No personalized recommendations
No new menus, filters, pages, or navigation
No changes to the M3 scoring model

The only change: Hidden Gem badge on qualifying title tiles, plus the fixed “Highly rated, rarely watched” line on the title detail sheet.

## Formalize your hypothesis & shipping criteria
- **Your hypothesis (filled in):** I believe that Hidden Gem Badge for For my persona, A long-term, frequent viewer who values discovering good content but is overwhelmed by StreamLine’s large catalog. (goal: Find something genuinely worth watching quickly without spending a large part of the evening browsing.), identify the specific external tools or manual processes they use to bypass their friction: After 20 minutes of scrolling, they still cannot find anything they want to watch and close StreamLine, sometimes turning to an alternative like a DVD instead. will result in More Coordinators complete the digital workflow instead of relying on manual workarounds, reducing wasted time and improving account satisfaction, which should support retention and reduce churn risk., as measured by a 10% relative improvement change in Compliance Check completion rate, increasing from the current 48% by at least 20% relative (to ~58%). within 14 days. We will protect Average viewer satisfaction must not decrease , and the early playback exit rate must not increase. throughout the test.
- **Your shipping criteria (filled in):** We will SHIP if Compliance Check completion rate, increasing from the current 48% by at least 20% relative (to ~58%). improves by ≥ 10% relative improvement at 5% (α = 0.05) and Average viewer satisfaction must not decrease , and the early playback exit rate must not increase. does not reach Average viewer satisfaction must not decrease by more than 5%, and the early playback exit rate must not increase by more than 5% relative to the baseline. Investigate if either threshold is exceeded. after 14 days. We will ITERATE if direction is positive but lift is below MDE. We will KILL if the primary metric shows no improvement or moves negatively. The read date is fixed at the end of 14 days, no results reviewed before then.
- **Hardest parameter to define, and did it change your hypothesis? quick debrief:** Hardest parameter to define: the MDE and primary success metric. I initially mixed the broader goal of reducing browsing frustration with the measurable outcome. Defining the test around 30+ minute sessions, with a 10% relative improvement from the 48% baseline, made the hypothesis more concrete and testable.

Did it change the hypothesis? Not fundamentally. It sharpened it: the hypothesis is specifically that the Hidden Gem badge helps viewers find something worth watching faster, rather than generally improving satisfaction or retention.
