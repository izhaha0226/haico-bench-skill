# haico-bench-skill

A public skill package for benchmark-aware Human-AI co-creation.

This repository is designed for creative and marketing workflows where the biggest failure mode is not "lack of output," but premature convergence: people often accept the first plausible AI result, then spend the rest of the session polishing an anchored idea.

haico-bench-skill addresses that problem by combining:
- HAICo-style divergence → selection → convergence
- benchmark-aware prompting
- anti-fixation checks before final execution

## Why this exists

Most creative prompting fails in one of two ways:
1. it asks for the final deliverable too early
2. it uses benchmarks as copying targets rather than structural references

This repo treats AI as a co-creator for exploration first, and as a production engine only after a direction is selected.

## Core workflow

1. Divergence
   - generate 5-9 meaningfully distinct directions
   - force distant analogies and non-obvious framings
2. Benchmark mapping
   - connect each direction to reusable benchmark structures
   - never copy benchmark phrasing verbatim
3. Selection
   - compare ideas on distinctiveness, fit, execution ease, scalability
4. Convergence
   - refine only the chosen direction
5. Anti-fixation check
   - confirm the team explored enough before finalizing

## Repository structure

- `SKILL.md` — main skill definition
- `prompts/haico-bench-prompts.md` — reusable prompt sequence
- `examples/marketing-copy.md` — example for copy/concept work
- `examples/card-news.md` — example for card-news / multi-slide ideation
- `references/further-reading.md` — papers and background references

## What this skill is for

- marketing concepts
- ad creatives
- campaign hooks
- card news
- thumbnails
- landing concepts
- early-stage content strategy

## What this skill is not for

- direct plagiarism from competitors
- one-shot final-output prompting
- benchmark imitation disguised as strategy

## Benchmark safety rules

Allowed:
- hook structure
- CTA structure
- tone density
- format preference
- information rhythm

Disallowed:
- verbatim competitor phrasing
- near-duplicate sentence patterns
- brand-specific slogans or claims
- benchmark outputs used as direct copy material

## Quick start

Use the prompt sequence in `prompts/haico-bench-prompts.md`.

Minimal starter:

"Give me 7 clearly different creative directions for this task. Do not produce the final deliverable yet. For each direction include metaphor, hook, CTA style, channel fit, benchmark-fit note, and risk. Then compare and rank the top 2 before refining only the winner."

## Example applications

- a social campaign concept informed by top-performing benchmark hooks
- a card-news narrative structure aligned with category benchmark rhythm
- a thumbnail angle exploration workflow before visual production
- a landing-page headline exploration workflow before copywriting

## Design principle

The main idea is simple:

Different before better.

Do not optimize an idea before proving it deserves optimization.

## References

See `references/further-reading.md` for papers on:
- design fixation
- divergent/convergent ideation
- human-AI co-creation
- benchmark-aware creative workflows

## License

MIT
