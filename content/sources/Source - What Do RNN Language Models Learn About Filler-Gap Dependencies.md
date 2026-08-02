---
title: Source - What Do RNN Language Models Learn About Filler-Gap Dependencies
type: source
status: active
updated: 2026-07-27
ingestion_depth: brief
tags:
  - source
  - brief
  - evaluation
  - syntax
  - filler-gap
  - language-models
---

## Summary
Wilcox, Levy, Morita, and Futrell test whether RNN language models represent long-distance filler-gap dependencies and some classic island constraints. Using controlled sentences and surprisal-based analysis, they find that LSTMs capture several filler-gap generalizations and show sensitivity to some island constraints, though not all. For WoLaLa, the paper is a useful bridge between theoretical syntax and evaluation methodology because it asks a precise competence question about a classic dependency rather than relying on broad benchmark scores.

## Strand Connections

- Primary: [[../overviews/Applications and Best Practices Overview|Applications and Best Practices]] (strand 6)
- Secondary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)

## WoLaLa Relevance
This source is valuable because it tests a substantive syntactic dependency that has long mattered in acquisition and formal-language debates. The result is mixed in an informative way: current RNNs learn some real structural generalizations, but their sensitivity to constraints is incomplete. That makes the paper more useful than both blanket success claims and blanket failure claims.

## Key Points
- The study targets filler-gap dependencies rather than simpler local agreement phenomena.
- It uses controlled stimuli and surprisal comparisons to detect whether gaps are being licensed.
- The models show evidence for several island constraints, but not uniformly.
- The paper demonstrates partial but incomplete syntactic generalization in state-of-the-art RNNs.

## Related Pages
- [[../overviews/Applications and Best Practices Overview|Applications and Best Practices Overview]]
- [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models Overview]]
- [[../sources/Source - Structural, Functional, and Processing Perspectives on Linguistic Island Effects|Source - Structural, Functional, and Processing Perspectives on Linguistic Island Effects]]
- [[../sources/Source - Targeted Syntactic Evaluation of Language Models|Source - Targeted Syntactic Evaluation of Language Models]]

## Source Identification
- Authors: Ethan Wilcox, Roger Levy, Takashi Morita, and Richard Futrell
- Title: "What do RNN Language Models Learn about Filler-Gap Dependencies?"
- Year: 2018
- Source type: workshop paper
- Publication: *Proceedings of BlackboxNLP 2018*, pages 211-221

## Source Access
- Public source: [ACL Anthology page](https://aclanthology.org/W18-5423/)
