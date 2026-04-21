# haico-bench-skill

## 한국어 소개

haico-bench-skill은 벤치마크를 참고하되 모방하지 않고,
AI와 함께 "발산 → 선택 → 수렴" 순서로 더 좋은 크리에이티브 결과물을 만들기 위한 스킬 패키지입니다.

이 레포가 해결하려는 핵심 문제는 단순히 "결과물이 별로다"가 아닙니다.
진짜 문제는 AI가 그럴듯한 첫 답을 너무 빨리 내놓고,
사람이 그 첫 답에 고정되어 계속 다듬기만 하게 되는 것입니다.

그 순간 작업은
- 탐색보다 polishing 중심이 되고
- benchmark-aware가 아니라 benchmark-shaped가 되며
- 평균 이상이지만 기억에 남지 않는 결과로 수렴합니다.

이 스킬은 그걸 막기 위해 설계되었습니다.

핵심 원칙:
- Different before better
- Chosen before polished
- Benchmark-aware before benchmark-shaped

### 이 스킬이 하는 일
- 발산형 아이데이션 강제
- 벤치마크 구조 추출
- 방향별 점수 평가
- 승자만 수렴
- 최종 anti-fixation 점검

### 이런 작업에 사용합니다
- 광고 카피
- 카드뉴스
- 랜딩페이지 콘셉트
- 썸네일 방향성
- 캠페인 훅
- 브랜드 카피 시스템
- 벤치마크 기반 크리에이티브 전략

### 이런 작업에는 쓰지 않습니다
- 단순 변환 작업
- 기계적 문서 정리
- 정답형 컴플라이언스 출력
- 벤치마크 없이 바로 1회성 결과만 뽑는 작업

## 어떻게 쓰는지

기본 흐름은 6단계입니다.

1. Framing
- 문제 정의
- 제약 정리
- 성공 기준 정리

2. Divergence
- 5~9개 방향 생성
- 각 방향마다 worldview / hook / tone / CTA / risk 포함

3. Benchmark mapping
- benchmark의 훅 구조 / CTA 리듬 / 톤 밀도 / 포맷 선호를 구조로만 매핑

4. Selection
- 점수표로 top 2만 남김
- 왜 1등이 이기고 2등이 지는지 설명

5. Convergence
- 1등만 실제 결과물로 수렴
- A/B 훅, safety note, 실행 체크리스트 포함

6. Anti-fixation review
- 진짜 탐색했는지
- benchmark 모방이 아닌지
- 방향 차이가 worldview 수준인지 점검

## 사용 예시

### 예시 1) 인스타그램 광고 카피
입력:
- Topic: 프리미엄 한우 오마카세 런치
- Platform: Instagram
- Objective: 예약 전환
- Benchmark: 있음

지시 예시:

"이 작업에 대해 전혀 다른 방향 7개를 먼저 제안해줘. 최종 카피는 아직 쓰지 마. 각 방향마다 worldview, hook, CTA style, benchmark-fit note, risk를 포함해줘. 그 다음 score table로 top 2만 남기고, 1위만 인스타그램 카피로 수렴해줘. 마지막에는 Instagram compression pass까지 실행해서 preview_lines와 final_shortened_version도 함께 줘."

### 예시 2) 카드뉴스 기획
입력:
- Topic: 봄철 레이저 시술 전후 주의사항
- Platform: Instagram card news
- Objective: 교육 + 상담 전환

지시 예시:

"카드뉴스 방향 5개를 먼저 제안해줘. 슬라이드 최종 문안은 아직 쓰지 마. 각 방향마다 narrative arc, hook strategy, CTA strategy, benchmark-fit note, risk를 포함해줘. 이후 top 2를 고르고, 1위만 6-slide 구조로 수렴해줘."

### 예시 3) 랜딩페이지 콘셉트
입력:
- Topic: 프리미엄 1:1 퍼스널 컬러 진단
- Platform: web landing page
- Objective: lead generation

지시 예시:

"랜딩 방향 7개를 제안해줘. final landing copy는 아직 쓰지 마. 각 방향마다 hero worldview, headline direction, proof strategy, CTA rhythm, benchmark-fit note, risk를 포함해줘. score table로 top 2만 남기고, 1위만 hero angle / hero headline / 4-section arc / proof strategy / CTA rhythm까지 수렴해줘."

## 빠른 시작

아래 프롬프트 한 줄로 시작할 수 있습니다.

"Generate 7 clearly different directions for this task. Do not produce the final deliverable yet. For each direction include worldview, hook, CTA style, benchmark-fit note, and risk. Then evaluate all directions with an explicit score table, keep only the top 2, and refine only the winner. Run an anti-fixation review before finalizing."

---

## English Overview

A benchmark-aware Human-AI co-creation skill for creative work that must be both original and effective.

This repository is built around one idea:

The enemy is not only bad output.
The real enemy is premature convergence on the first plausible output.

When that happens, benchmark-aware work becomes benchmark-shaped work.
The result may be competent, but it is rarely memorable.

haico-bench-skill is designed to stop that.

## What this skill does

It combines:
- divergence-first ideation
- benchmark-aware structural mapping
- explicit direction scoring
- controlled convergence
- anti-fixation review before finalization

The quality standard is not "usable."
The quality standard is "worth sharing."

## Why this exists

Most creative prompting fails because it:
1. asks for the final deliverable too early
2. mistakes benchmark imitation for benchmark intelligence
3. confuses variation with divergence
4. polishes before choosing

This repository treats AI as:
- a co-creator during exploration
- a judge during selection
- a production engine only after a direction is chosen

## Core workflow

1. Framing
2. Divergence
3. Benchmark mapping
4. Selection
5. Convergence
6. Anti-fixation review

## Repository structure

- `SKILL.md` — main skill definition
- `prompts/haico-bench-prompts.md` — reusable prompt sequence
- `examples/marketing-copy.md` — copy / caption example
- `examples/card-news.md` — card-news example
- `examples/landing-concept.md` — landing concept example
- `examples/thumbnail.md` — thumbnail ideation example
- `examples/campaign-strategy.md` — campaign strategy example
- `examples/haico-example-updated.md` — compact worked example from Chief/OpenClaw practice
- `references/failure-modes.md` — known failure patterns
- `references/scoring-rubric.md` — explicit evaluation model
- `references/output-schema.md` — standardized output packaging
- `references/further-reading.md` — background reading and papers

## What this skill is for

- ad creatives
- campaign hooks
- landing concepts
- thumbnails
- card news
- branded copy systems
- concept decks
- benchmark-aware content strategy

## What this skill is not for

- direct competitor imitation
- one-shot final-output prompting
- cosmetic rewrites of benchmark winners
- safe-but-generic category language presented as originality

## Benchmark safety rules

Allowed:
- hook structure
- CTA rhythm
- tonal density
- pacing logic
- format preference
- information ordering

Disallowed:
- verbatim competitor phrasing
- near-duplicate sentence skeletons
- recognizable competitor slogans
- signature campaign logic copied with synonyms
- benchmark outputs used as raw copy source

## Quick start

Use the prompt sequence in `prompts/haico-bench-prompts.md`.

Minimal starter:

"Generate 7 clearly different directions for this task. Do not produce the final deliverable yet. For each direction include worldview, hook, CTA style, benchmark-fit note, and risk. Then evaluate all directions with an explicit score table, keep only the top 2, and refine only the winner. Run an anti-fixation review before finalizing."

## Practical recommendation

If the output already feels good on the first pass, be more suspicious, not less.
That often means fixation pressure has already started.

## References

Use the `references/` folder if you need:
- failure diagnosis
- stronger selection discipline
- standardized output packaging
- research context for design fixation and Human-AI co-creation

## License

MIT
