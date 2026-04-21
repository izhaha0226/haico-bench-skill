---
name: haico-bench-skill
description: Use when creative or marketing work risks premature convergence on the first plausible AI output, especially when benchmarks are present and must inform structure without causing imitation.
---

# HAICo Bench Skill

## Core insight
The main failure in AI-assisted creative work is often not lack of ideas, but early fixation.
If the model presents a plausible answer too quickly, humans tend to switch from exploration to polishing.
That creates anchored, benchmark-shaped, slightly-above-average work.

This skill exists to prevent that.
It combines:
- HAICo divergence-first ideation
- benchmark-aware structural extraction
- explicit evaluation before refinement
- anti-fixation review before final output

The standard is not "usable."
The standard is "worth sharing."

## When to use
Use this skill when:
- the task is creative, persuasive, or concept-led
- the first plausible idea is likely to dominate discussion
- benchmarks or reference channels are involved
- originality matters as much as performance logic
- the final output must feel intentionally chosen, not merely generated

Typical triggers:
- ad creatives
- campaign hooks
- landing page concepts
- thumbnails
- card news
- branded copy systems
- concept decks
- channel strategy angles

## When NOT to use
Do not use this skill when:
- the task is purely mechanical or clerical
- the desired output is a direct format transformation
- benchmarks are unnecessary
- the task requires exact compliance rather than ideation
- the user explicitly wants a single direct answer with no exploration

## Inputs required
Before starting, define these explicitly:
- task_type
- topic
- platform
- target audience
- industry or category
- objective
- novelty target: low / medium / high
- execution depth: exploratory / decision-ready / production-ready
- benchmark state: none / weak / strong
- hard constraints
- disallowed patterns

## Non-negotiable rules
- Never finalize on turn 1.
- Never confuse variation with divergence.
- Never use benchmark wording as copy source.
- Never evaluate while still pretending to explore.
- Never blend top directions prematurely.
- Never claim originality if benchmark distance is low.
- Never ship before anti-fixation review.

## Benchmark doctrine
Benchmarks are for structure, not imitation.

Allowed benchmark extraction:
- hook shape
- CTA rhythm
- tonal density
- pacing
- format preference
- information ordering
- conversion mechanics

Disallowed benchmark usage:
- verbatim phrasing
- near-duplicate sentence construction
- signature slogans
- recognizable campaign logic tied to one competitor
- cosmetic synonym swaps over copied structure

## Workflow

### Stage 1 — Framing
Define:
- problem statement
- constraints
- success criteria
- novelty target
- execution depth

Output:
- 1 sentence problem framing
- bullet constraints
- bullet success criteria

Goal:
Make the creative problem legible before ideation begins.

### Stage 2 — Divergence
Generate:
- 5 to 9 genuinely different directions

Every direction must include:
- direction name
- core metaphor or worldview
- one-line hook
- emotional tone
- best-fit channel
- CTA style
- benchmark-fit note
- main risk

Divergence must happen at the level of:
- worldview
- persuasion mechanism
- audience emotion
- information architecture
- format logic

Not enough:
- same concept with different adjectives
- same hook with different nouns
- same benchmark style with cleaner wording

### Stage 3 — Benchmark mapping
Map each direction structurally against benchmark logic.

Check:
- hook pattern fit
- CTA structure fit
- tone density fit
- format fit
- audience energy fit
- derivative risk

Goal:
Use benchmark intelligence without collapsing into mimicry.

### Stage 4 — Selection
Score each direction using explicit criteria.

Minimum criteria:
- distinctiveness
- brand fit
- execution ease
- scalability
- benchmark-fit quality
- channel suitability
- originality risk

Selection rule:
- choose top 2 only
- explain why #1 wins
- explain why #2 loses
- do not converge all 7 into a hybrid mess

### Stage 5 — Convergence
Refine only the winning direction.

Depending on task type, produce:
- copy
- slide structure
- headline system
- thumbnail angle
- landing section narrative
- concept summary

Required add-ons:
- A/B hook variants
- benchmark safety note
- execution checklist

### Stage 6 — Anti-fixation review
Before finalizing, answer:
- Did we actually explore enough?
- Were the directions worldview-different or only cosmetically different?
- Did benchmark usage stay structural?
- Did evaluation happen after generation, not during it?
- Is the final result original enough for the stated novelty target?
- If not, should we branch again?

## Branching rules

### If divergence is weak
Re-run Stage 2 with one of these instructions:
- increase metaphor distance
- force category inversion
- force non-obvious emotional frame
- ban the current top concept family

### If benchmark gravity is too strong
Re-run Stage 3 with:
- benchmark-distance emphasis
- explicit ban on copied cadence
- competitor-recognition test

### If top 2 are too similar
Reject both and regenerate.
Similarity at worldview level means failure.

### If final output is polished but unsurprising
This is fixation disguised as refinement.
Go back to Stage 2 or Stage 4.

## Quality bar by novelty target

### Low novelty
- recognizable category language acceptable
- modest differentiation sufficient
- benchmark gravity can be higher

### Medium novelty
- at least one clear conceptual twist required
- output must feel chosen, not generic
- benchmark distance should be visible

### High novelty
- worldview shift required
- remote analogy or category break strongly recommended
- derivative risk must be explicitly addressed
- if it feels category-native in an obvious way, it is probably not enough

## Output standards by task type

### Copy
Must include:
- chosen direction
- final hook
- body
- CTA
- hashtags or extension assets if relevant
- 2 A/B hook variants
- safety note

### Card news
Must include:
- chosen direction
- slide goal per slide
- slide headline
- slide body idea
- visual direction
- CTA placement
- A/B opening hooks

### Landing concept
Must include:
- hero angle
- subhead logic
- section narrative arc
- proof strategy
- CTA rhythm
- benchmark safety note

### Thumbnail
Must include:
- thumbnail concept names
- primary contrast
- text-on-image options
- visual tension note
- curiosity mechanism
- clickbait safety note

## Red flags
If you see any of these, stop and re-branch:
- "This is probably good enough"
- "The first one was strongest anyway"
- "Let’s just tweak the wording"
- "It sounds like benchmark winners, so it should work"
- "These 7 are different enough" when they share one worldview
- "We already have a usable answer"

All of these indicate fixation pressure.

## What strong output feels like
A strong result should:
- feel structurally informed but not traceable to one competitor
- show a deliberate point of view
- survive human critique as a chosen concept
- be compressible into execution without losing its spine
- make the second-best direction feel meaningfully different, not almost identical

## Failure modes
Common failures are documented in `references/failure-modes.md`.
Use that file when the work looks polished but suspiciously familiar.

## Worked example
Use `examples/haico-example-updated.md` when a compact end-to-end sample is needed.
It shows the minimum viable HAICo loop with input, 5-way divergence, explicit selection, converged output, visual direction, and delivery rules.

## Scoring rubric
Use `references/scoring-rubric.md` when the team needs more disciplined direction comparison.

## Output schema
Use `references/output-schema.md` for standardized final packaging.

## Prompt starter
"Generate 7 clearly different directions for this task. Do not produce the final deliverable yet. For each direction include worldview, hook, CTA style, benchmark-fit note, and risk. Then evaluate all directions with an explicit score table, keep only the top 2, and refine only the winner. Run an anti-fixation review before finalizing."

## Final principle
Different before better.
Benchmark-aware before benchmark-shaped.
Chosen before polished.
Shareable before merely usable.
