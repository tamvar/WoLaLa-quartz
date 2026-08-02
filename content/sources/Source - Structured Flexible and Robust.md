---
title: Source - Structured Flexible and Robust
type: source
status: active
updated: 2026-07-29
ingestion_depth: brief
tags:
  - source
  - brief
  - reasoning
  - ood-generalization
  - hybrid-models
  - cognition
---

## Summary
Katherine M. Collins, Catherine Wong, Jiahai Feng, Megan Wei, and Joshua B. Tenenbaum compare humans and language models on out-of-distribution reasoning tasks and find a substantial robustness gap. Their proposed hybrid Parse-and-Solve model, which combines language understanding with a structured symbolic reasoning component, performs better on the hardest planning cases than pure distributional language models. For WoLaLa, the paper matters because it separates human-like output patterns from the deeper question of what cognitive organization supports robust reasoning.

## Strand Connections

- Primary: [[../overviews/Cultural, Cognitive, and SSH Perspectives Overview|Cultural, Cognitive, and SSH Perspectives]] (strand 5)
- Secondary: [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering]] (strand 7)

## WoLaLa Relevance
This source is useful because it avoids two equally simple stories. It does not conclude that language models cannot reason at all, but it also does not treat partial behavioral success as evidence that they have human-like reasoning architecture. The benchmark is designed to stress structure, flexibility, and robustness under distribution shift, which makes the human-model comparison more informative than ordinary in-distribution accuracy.

The hybrid model result also matters. It provides a concrete example of a constructive alternative in which language modeling is paired with a more explicit reasoning substrate. That makes the source an important bridge between cognition-facing evaluation and mind-design questions about how language-capable reasoning systems should be built and explained.

## Key Points
- The paper introduces an out-of-distribution reasoning benchmark spanning planning and explanation-generation tasks.
- Humans remain much more robust than pure language models on the benchmark.
- A hybrid Parse-and-Solve system improves robustness by adding a structured symbolic reasoning component.
- The result supports a distinction between superficial task success and more human-like structured reasoning.

## Limitation Or Open Question
The benchmark covers a bounded set of reasoning tasks, and the hybrid system includes hand-specified structure. The main open question is whether similarly robust structure can emerge inside large learned systems, or whether some explicit decomposition will remain necessary for strong out-of-distribution reasoning.

## Related Pages
- [[../overviews/Cultural, Cognitive, and SSH Perspectives Overview|Cultural, Cognitive, and SSH Perspectives Overview]]
- [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering Overview]]
- [[../sources/Source - Language Models Show Human-Like Content Effects on Reasoning Tasks|Source - Language Models Show Human-Like Content Effects on Reasoning Tasks]]
- [[../sources/Source - Building Machines That Learn and Think Like People|Source - Building Machines That Learn and Think Like People]]
- [[../sources/Source - Dissociating Language and Thought in Large Language Models|Source - Dissociating Language and Thought in Large Language Models]]

## Source Identification
- Authors: Katherine M. Collins, Catherine Wong, Jiahai Feng, Megan Wei, and Joshua B. Tenenbaum
- Title: *Structured, Flexible, and Robust: Benchmarking and Improving Large Language Models Towards More Human-Like Behavior in Out-of-Distribution Reasoning Tasks*
- Year: 2022
- Source type: preprint
- Publication context: arXiv `2205.05718`

## Source Access
- Public source: [arXiv abstract page](https://arxiv.org/abs/2205.05718)
