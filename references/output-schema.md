# Output Schema

Use this schema for final packaging.

## Divergence schema
For each direction:
- direction_name
- worldview
- hook
- emotional_tone
- best_fit_channel
- cta_style
- benchmark_fit_note
- risk

## Selection schema
- score_table
- top_1
- top_2
- why_top_1_wins
- why_top_2_loses
- regenerate_required: true/false

## Final output schema by task type

### Copy
- chosen_direction
- final_hook
- body
- cta
- hashtags
- hook_variants
- benchmark_safety_note
- execution_checklist

### Card news
- chosen_direction
- slides[]
  - slide_goal
  - slide_headline
  - slide_body_idea
  - visual_direction
  - cta_placement
- hook_variants
- benchmark_safety_note
- execution_checklist

### Landing concept
- chosen_direction
- hero_angle
- hero_headline
- hero_subhead
- sections[]
  - section_name
  - section_goal
  - narrative_logic
- proof_strategy
- cta_rhythm
- benchmark_safety_note

### Thumbnail
- chosen_direction
- thumbnail_options[]
  - concept_name
  - primary_contrast
  - image_logic
  - text_on_image
  - curiosity_mechanism
- click_safety_note

## Anti-fixation review schema
- explored_enough: yes/no
- worldview_diversity_confirmed: yes/no
- benchmark_structural_only: yes/no
- evaluation_separated_from_generation: yes/no
- novelty_target_met: yes/no
- rebranch_required: yes/no
- final_verdict
