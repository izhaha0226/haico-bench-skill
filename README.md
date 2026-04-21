# haico-bench-skill

HAICo bench skill for Human-AI co-creation workflows.

Purpose:
- prevent first-result anchoring
- force divergent exploration before convergence
- make creative prompting more benchmark-aware

Core flow:
1. Divergence: generate 5-9 distinct directions
2. Selection: compare and rank directions
3. Convergence: refine only the chosen direction
4. Anti-fixation check: verify we did not just polish the first plausible idea

This repository packages the core HAICo skill prompt and a benchmark-oriented extension for creative/marketing workflows.

## Files
- `SKILL.md`: main skill definition
- `prompts/haico-bench-prompts.md`: prompt sequence for divergence → selection → convergence

## Use cases
- marketing concepts
- ad creatives
- card news
- thumbnails
- landing concepts
- campaign hooks

## Philosophy
AI should not be treated as a one-shot output machine for creative work. It works better as a co-creator when exploration and refinement are separated.
