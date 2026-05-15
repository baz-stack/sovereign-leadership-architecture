---
description: Run the Five Imposters check — which of the five false solutions has the user already invested in.
argument-hint: "[optional: list the programs/interventions you've already tried]"
---

Run the Five Imposters™ check from the SLA methodology.

The Five Imposters are the five systems high-achieving leaders invest in repeatedly that treat the symptom and leave the structure untouched:

1. **The Motivation Machine** — speakers, breakthrough weekends, Tony Robbins-style events
2. **The Therapy Loop** — years of therapy, deep insight, processing without architectural installation
3. **The Hustle Gospel** — more output, more discipline, 5AM routines, grinding through
4. **The Mindset Myth** — NLP, journaling, affirmations, "rewire your brain" frameworks
5. **The Group Container** — masterminds, peer groups, cohort programs

If `$ARGUMENTS` is provided, parse what the user has listed and map each item to the Imposter(s) it represents. If not, ask the user to list the programs, coaches, masterminds, courses, therapists, and interventions they've invested in over the last 3–5 years (and approximate spend if known).

Then produce a reading that:

- Names which Imposters the user has invested in (3 or more is the threshold pattern)
- For each Imposter present, names *what it masked* — which RAMS pillar or Six Drive is the underlying fracture the Imposter was treating around
- Closes with the SLA reframe: this is not failure. It is data. The interventions were not designed for the level of the problem. The root is identity infrastructure.

Use the SLA voice — load the `sla-voice-standards` skill if you have not already. Reference `FRAMEWORKS.md` and `frameworks/five-imposters.md` for canonical language. Do not invent — excavate.
