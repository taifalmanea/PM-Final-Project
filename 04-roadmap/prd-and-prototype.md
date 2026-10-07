# PRD & Prototype Sprint (Module 4)

## Pick & scope with MoSCoW
- **The “Now” feature I’m scoping (name + one-line core description):** Hidden Gem Badge (A3): a badge on high-quality, low-view titles identified by M3 data, so viewers can find great content in the existing catalog without having to dig for it.
- **My finalized Must-Haves (after overriding the AI):** Gem selection rule with a hard cap. M3 identifies titles above a quality threshold and below a view threshold, and a fixed cap limits how many are badged at once. The cap is a parameter of the rule rather than a separate requirement, because without it the badge adds to the overload instead of reducing it.
One-time static gem list. The rule is run once, and the result ships as a static list the app reads. There is no pipeline and no scheduled job.
"Hidden Gem" text badge on the shared title tile. It is visible without hover or tap and has a screen-reader label. Because it lives on the shared tile component, it appears on home rows and in the Spotlight Curated Rail without separate builds, and if A1 slips, the badge still ships on home rows.
- **What I demoted from Must → Should/Won’t, and why:** Playable titles only (M3) → Should. The browse surfaces already hide unavailable titles, so the badge inherits that filter for free. The only remaining risk is a licence expiring while a title is badged, and the suppression list (S5) handles that more cheaply than building expiry logic.

Readable text label (M5) → merged into the badge requirement, not demoted. It was a design spec for the badge rather than a separate deliverable, and splitting it out made the must-have list look bigger than the actual work.

## Generate your Simplified PRD
- **One thing my PRD makes explicit that a vague brief would have missed:** The hard cap of 8 badged titles (FR2), with a tie-break rule for when more qualify.

A vague brief like "badge high-quality, low-view titles" would have badged everything M3 flags, possibly hundreds of titles in a 15,000-title catalog. That turns the badge into one more thing to scan, which recreates the 20-minute browsing problem it was meant to solve. Writing in the cap, plus the rule for which 8 win (highest rating first, then lowest views), makes the badge scarce enough to actually shorten the decision.

## Prompt-to-prototype sprint
- **Where did the prototype reveal a gap in my PRD logic? (what I had to update):** "Bottom 25% of views" doesn't say what to count.

It doesn't say whether titles with missing data or marked unavailable count toward the 25%. I left them out, so the 25% was taken from 38 titles, not 40.
25% of 38 is 9.5, and the PRD doesn't say whether to round up or down. I rounded up to 10.
It doesn't say what happens when two titles tie on views at the cutoff. I included both.
Fix: define the group being measured, the rounding, and how ties are handled.
- **My prototype, as a link or a screenshot (publish or share from your tool; in Lovable that is Share → Share Preview, in Bolt Publish → Web. No share URL? Screenshot the working flow):** https://flow-spotlight-show.lovable.app
