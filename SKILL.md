---
name: haico-bench-skill
description: HAICo benchmark-oriented skill. Use for creative and marketing tasks that require divergent ideation first, then convergent refinement, while referencing benchmark patterns without copying them.
---

# HAICo Bench Skill

## Goal
Combine HAICo's divergence-first workflow with benchmark-aware execution.

## Core rules
- Never finalize on turn 1.
- Generate multiple distinct directions first.
- Use benchmark patterns as structural references only.
- Never copy benchmark phrasing verbatim.
- Separate generation, evaluation, and refinement.

## Workflow
1. Divergence
   - generate 5-9 distinct angles
   - include remote analogies and contrarian framings
2. Benchmark mapping
   - extract reusable hook/CTA/tone patterns
   - map which directions fit which benchmark patterns
3. Selection
   - score for distinctiveness, fit, execution ease, scalability
4. Convergence
   - refine only top 1-2 directions
5. Anti-fixation check
   - confirm we explored enough before refining

## Output shape
For each direction include:
- direction name
- core metaphor
- hook idea
- CTA style
- channel fit
- benchmark-fit note
- risk

## Benchmark safety
Allowed:
- hook structure
- CTA structure
- tone density
- format preference

Disallowed:
- verbatim copying
- near-duplicate sentence structure
- competitor-specific slogans

## Prompt starter
"Give me 7 clearly different creative directions for this task. Do not produce the final deliverable yet. For each direction include metaphor, hook, CTA style, channel fit, benchmark-fit note, and risk. Then rank the top 2 only after comparison."
