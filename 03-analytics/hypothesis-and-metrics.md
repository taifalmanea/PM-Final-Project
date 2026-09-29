# Hypothesis & Success Metrics (Module 3)

## Pre-work · Hypothesis check
- **Role , who you are solving for (from M2):** A long-term, frequent viewer who values discovering good content but is overwhelmed by StreamLine’s large catalog.
- **Goal , what this user is ultimately trying to achieve:** Find something genuinely worth watching quickly without spending a large part of the evening browsing.
- **Friction / moment of misery , the specific pain blocking their goal:** After 20 minutes of scrolling, they still cannot find anything they want to watch and close StreamLine.
- **Current workaround , the external tool or manual process they rely on (M2):** They abandon StreamLine and turn to an alternative source, such as a DVD.
- **Problem Hook , your one-sentence framing of the business crisis (M1):** StreamLine has plenty to watch, but users can’t easily find what’s worth watching putting engagement and retention at risk.
- **Value Proposition , the outcome your initiative promised to deliver (M1):** Spotlight turns StreamLine from a warehouse of 15,000 titles into a curated destination for quality content, helping users quickly discover what is worth watching and giving StreamLine a stronger reason to stay competitive now.

## Read your data snapshots
- **Does the funnel data confirm your M2 friction point, or does it tell a different story? Note where the numbers align with the qualitative pain you found and where they diverge.:** The funnel data confirms the M2 friction point, but adds an important nuance: the problem is not getting users into the catalog; it is helping them find something worth watching and stay engaged. Only 11% of homepage visitors reach a 30+ minute session, down from 19%, supporting the qualitative finding that users struggle to find something compelling enough to watch. The share of users who search and then play fell from 41% to 34%, suggesting that users are becoming less successful at turning intent into actual viewing.
- **Do the retention patterns align with the workaround your M2 persona used to find content? Note what the Mo. 0→1 drop suggests about the onboarding experience your persona described as frustrating.:** The retention patterns align with the M2 workaround. The persona struggles to find something worth watching, spends time browsing, and may leave the platform entirely. The cohort data shows that this early experience has a meaningful impact on whether users continue with StreamLine.  Full-Library cohorts retain only 63–68% at Month 1, meaning roughly one-third of users are already lost after the first month.
- **Does the LTV gap and the content mix (61% trending for Wanderers) confirm the moment of misery your persona described? Note which segment your persona is in and whether the data confirms their pain.:** Yes, the data confirms the moment of misery, but it also changes which segment should be the primary focus.

Persona alignment: The Quality-Seeking Heavy Viewer maps most closely to Power Users because they are frequent viewers and value discovering quality content.
Pain is still supported: Power Users consume 58% curated content, which is consistent with the persona’s preference for quality-focused discovery. However, their $14.20 LTV and 4.8 sessions/week show that they are already highly engaged.
The bigger opportunity: Wanderers make up 41% of the user base, have the lowest LTV ($8.40) and lowest engagement (1.1 sessions/week), and show the largest churn improvement when exposed to Spotlight (22 points).
Important nuance: Wanderers consume 61% trending content, suggesting their behavior is more aligned with broad/trending discovery than the quality-seeking persona originally described.

Conclusion: The qualitative persona accurately captured a real discovery problem, but the quantitative data suggests that Wanderers represent a larger business opportunity for Spotlight. The initiative may therefore need to expand beyond solving the frustration of heavy quality-seeking viewers to helping less-engaged users discover content that brings them back.
- **Does the low adoption confirm your persona is burdened by tools they don’t use? Note whether the low scheduling adoption (42%) for coordinators matches your M2 moment of misery.:** Yes, the adoption data partially confirms the persona’s frustration, particularly for Coordinators, but it also adds nuance about where the friction sits.

Core tools are widely used: Coordinators heavily use the Live Dispatch Board (91%), Route Optimizer (85%), and Compliance Checklist (77%), so their frustration is not caused by simply having too many unused tools.
Scheduling is a clear adoption gap: Only 42% of Coordinators use the Shift Scheduling Module, compared with 79% of Managers. This supports the M2 finding that scheduling may be creating friction for Coordinators.
AI Predictive ETAs are not a primary driver: Adoption is only 23% among Coordinators and 11% among Drivers, despite being a headline investment. This suggests the feature has not translated into regular frontline usage.
Persona fit: The Coordinator persona appears most relevant because they rely heavily on the core operational tools but have lower adoption of scheduling.

Conclusion: The data supports the M2 pain around scheduling, but suggests the broader issue is not tool overload. It is more specifically an adoption and workflow-fit problem around features such as scheduling.
- **Does the workflow data match the manual process or hack you documented in M2? Note whether the specific drop-offs or time gaps explain why your persona avoids the digital tool.:** Yes, the workflow data strongly matches the M2 manual process and explains why the persona avoids the digital tool.

The biggest drop-off happens after route assignment: Only 48% continue to Log Compliance Checks, and just 31% complete the Shift Handoff.
Compliance is the clearest bottleneck: It takes 14.6 minutes vs. a 3-minute benchmark, an 11.6-minute gap and nearly 5× the expected time.
The time gaps accumulate: Route Assignment, Compliance Checks, Shift Handoff, and Daily Reporting all take substantially longer than the benchmark, creating a total of roughly 31 minutes of wasted time per day.
This explains the workaround: If the manual process is faster or easier than completing these steps digitally, Coordinators have a clear incentive to bypass the tool.

Conclusion: The quantitative data validates the M2 finding and pinpoints the main source of friction: the compliance-check workflow is the largest operational bottleneck, followed by handoff and reporting
- **Look at the CSAT heatmap. Which specific cell most directly maps to your persona’s friction? Note how the NPS trend justifies the urgency of your M1 Problem Hook.:** _(not filled in)_

## Step 3 · Craft your hypothesis
- **Qualitative evidence (from M2) , quote the specific friction / moment of misery for your persona:** The persona described having to rely on a manual workaround because the digital workflow was too cumbersome, particularly around compliance and handoff tasks.
- **Quantitative evidence (from M3) , name the metric or data point that confirms the pain; cite the number:** Only 48% of Coordinators reach the Compliance Check step, and the task takes 14.6 min vs. a 3-min benchmark. Coordinator Compliance CSAT is 2.2/5.
- **Persona , role, goal, and the friction you confirmed in the reconciliation steps:** Coordinator — needs to complete daily dispatch operations efficiently, but avoids or abandons parts of the digital workflow because compliance and downstream tasks take too long.
- **Problem you are solving , one sentence describing the specific friction this initiative removes:** Reduce the time and friction required for Coordinators to complete compliance checks and continue through the daily dispatch workflow.
- **Strategic outcome , what behaviour change do you expect, and how does it map to retention / revenue / churn?:** More Coordinators complete the digital workflow instead of relying on manual workarounds, reducing wasted time and improving account satisfaction, which should support retention and reduce churn risk.
- **Primary success metric (initiative signal) , the leading indicator that tells you the gap is closing:** Compliance Check completion rate, increasing from the current 48% by at least 20% relative (to ~58%).
- **Guardrail metric (product signal) , the metric that must NOT drop; it protects your existing base:** Core Dispatch CSAT — currently 4.1/5 for Coordinators; it should not materially decline while the compliance workflow is improved.
- **Decision window , how much time or data before you scale, pivot, or kill? minimum threshold to proceed?:** 4–6 weeks after launch, with at least enough usage to establish a stable weekly trend. Proceed if Compliance completion improves by ≥20% relative and the guardrail remains stable; otherwise reassess or pivot
- **Draft your full hypothesis sentence , one to three sentences; quote the metric, name the persona, name the outcome:** Based on qualitative evidence of Coordinators relying on manual workarounds and quantitative evidence showing that only 48% reach Compliance Checks, with the task taking 14.6 minutes versus a 3-minute benchmark and receiving 2.2/5 CSAT, I believe that simplifying the Compliance workflow for Coordinators will increase digital workflow completion and reduce manual workarounds. I will target at least a 20% relative increase in Compliance Check completion, while protecting Core Dispatch CSAT, and will make a go/no-go decision after 4–6 weeks of post-launch data.
