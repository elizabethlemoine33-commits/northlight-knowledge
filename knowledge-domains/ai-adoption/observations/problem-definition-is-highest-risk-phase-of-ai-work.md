---
id: OBS-SOC-0004
title: Problem definition is the highest-risk phase of AI-assisted work
status: active
confidence: high
created: 2026-07-25
last_reviewed: 2026-07-25
category: observation
domain: ai-adoption
tags:
  - ai-adoption
  - ai-governance
  - critical-thinking
relationships:
  - ai-rollouts-fail-when-context-is-missing.md
  - vendor-selection-should-start-with-problems-not-tools.md
  - ../../knowledge-systems/observations/context-is-infrastructure-for-ai.md
  - ../../../evidence/linkedin-posts/EVD-SOC-0007-building-with-ai-posture-and-iteration.md
---

# Problem definition is the highest-risk phase of AI-assisted work

## Observation

The dominant concern about AI in professional work is execution risk — AI producing incorrect outputs, hallucinating facts, or generating plausible-sounding answers that are wrong. The more significant risk is earlier: AI that defines the problem on the user's behalf, and the user who accepts that framing without interrogating it.

AI amplifies the quality of thinking going in. If the problem definition is wrong, the output is confidently wrong at scale. The bottleneck for most people is not access to AI capability — it is clarity about what they are actually trying to solve.

"If you can't explain the problem to another person in plain language, you won't get a useful answer from AI."

## Interpretation

This has practical implications for AI rollout design. Training that focuses on prompt technique without training on problem definition addresses the less critical risk. The more useful capability is the ability to separate: what am I trying to understand? What decision am I trying to make? What would a good answer actually look like?

AI as a thinking partner to argue with, not a first draft to polish, is a posture that keeps problem definition in human hands.

## Evidence Needed

- Examples where accepted AI framing led to downstream errors that weren't caught because the output looked authoritative.
- Evidence on how problem definition quality correlates with output usefulness across different user groups.
- Counterexamples: cases where AI framing improved problem definition rather than distorting it.
