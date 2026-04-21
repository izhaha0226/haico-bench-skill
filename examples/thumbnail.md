# Example: Thumbnail Workflow

## Task
Create YouTube thumbnail directions that are benchmark-aware without becoming recognizable clones.

## Divergence prompt
Generate 7 thumbnail directions.
Do not finalize the thumbnail yet.
For each direction provide:
- concept name
- emotional trigger
- main contrast
- visual logic
- text-on-image option
- benchmark-fit note
- risk

## Selection prompt
Score each thumbnail direction on:
- stop-scroll power
- curiosity quality
- clarity at small size
- benchmark-fit
- originality risk
Return top 2 only.

## Convergence prompt
Refine only #1 into:
- 3 thumbnail variants
- image logic
- text-on-image options
- curiosity mechanism
- click-safety note

## Anti-fixation check
Before finalizing, answer:
- Is this actually distinctive at a glance?
- Are we using benchmark contrast structurally rather than copying visual tropes?
