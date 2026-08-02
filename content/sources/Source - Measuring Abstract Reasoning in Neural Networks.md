---
title: Source - Measuring Abstract Reasoning in Neural Networks
type: source
status: active
updated: 2026-07-29
ingestion_depth: brief
tags:
  - source
  - brief
  - reasoning
  - benchmark
  - ravens-matrices
  - generalization
---

## Summary
David G. T. Barrett, Felix Hill, Adam Santoro, Ari S. Morcos, and Timothy Lillicrap introduce a Raven-style benchmark for abstract visual reasoning and use it to test whether neural networks generalize relational structure or rely on superficial statistics. For WoLaLa, the source matters because it gives a compact and influential case where benchmark success depends on out-of-distribution generalization regimes, and where architectural choices plus symbolic explanations affect reasoning performance.

## Strand Connections

- Primary: [[../overviews/Cultural, Cognitive, and SSH Perspectives Overview|Cultural, Cognitive, and SSH Perspectives]] (strand 5)
- Secondary: [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering]] (strand 7)

## WoLaLa Relevance
This source primarily supports [[../overviews/Cultural, Cognitive, and SSH Perspectives Overview|Cultural, Cognitive, and SSH Perspectives]] and secondarily [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering]]. It is useful because it separates pattern recognition from stronger relational generalization. The paper shows that standard architectures can fail badly once train-test regimes diverge, while architectures designed for relation-sensitive reasoning do better but still have sharply bounded strengths.

## Limitation Or Open Question
The benchmark is visual and highly stylized, so it does not directly show how language models reason. The open question is how far the lesson transfers: does stronger performance on abstract reasoning tasks reveal a reusable cognitive ability, or only better fit to a particular benchmark family?

## Related Pages
- [[../overviews/Cultural, Cognitive, and SSH Perspectives Overview|Cultural, Cognitive, and SSH Perspectives Overview]]
- [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering Overview]]
- [[../sources/Source - TinyStories|Source - TinyStories]]
- [[../sources/Source - Language Models Show Human-Like Content Effects on Reasoning Tasks|Source - Language Models Show Human-Like Content Effects on Reasoning Tasks]]

## Source Identification
- Authors: David G. T. Barrett, Felix Hill, Adam Santoro, Ari S. Morcos, and Timothy Lillicrap
- Title: *Measuring Abstract Reasoning in Neural Networks*
- Year: 2018
- Source type: conference paper
- Publication: *Proceedings of the 35th International Conference on Machine Learning*

## Source Access
- Public source: [PMLR proceedings page](https://proceedings.mlr.press/v80/barrett18a.html)
- DOI / publisher: [arXiv abstract page](https://arxiv.org/abs/1807.04225)
