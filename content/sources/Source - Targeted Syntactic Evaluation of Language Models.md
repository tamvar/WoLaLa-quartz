---
title: Source - Targeted Syntactic Evaluation of Language Models
type: source
status: active
updated: 2026-07-27
ingestion_depth: brief
tags:
  - source
  - brief
  - evaluation
  - syntax
  - methodology
  - language-models
---

## Summary
Marvin and Linzen introduce a controlled evaluation dataset built from minimal pairs of grammatical and ungrammatical sentences targeting subject-verb agreement, reflexive anaphora, and negative polarity items. The paper argues that perplexity is too blunt to evaluate syntactic competence and shows that LSTM language models perform much worse on many controlled constructions than on broad held-out prediction metrics. For WoLaLa, it is an important methodology source because it helps define what language-focused evaluation should look like.

## Strand Connections

- Primary: [[../overviews/Applications and Best Practices Overview|Applications and Best Practices]] (strand 6)
- Secondary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)

## WoLaLa Relevance
This paper matters because it makes a durable methodological move: replace aggregate performance measures with carefully controlled grammatical contrasts. That move is central to WoLaLa, where the question is often not whether a model is broadly useful but whether it captures particular kinds of linguistic structure.

## Key Points
- The paper uses minimal-pair stimuli to isolate syntax-sensitive phenomena.
- It argues that perplexity confounds syntax with collocation, semantics, and pragmatics.
- LSTMs perform well on simpler cases but struggle on harder controlled constructions.
- Explicit syntactic supervision helps, but still leaves a substantial gap to human performance.

## Related Pages
- [[../overviews/Applications and Best Practices Overview|Applications and Best Practices Overview]]
- [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models Overview]]
- [[../sources/Source - A Systematic Assessment of Syntactic Generalization in Neural Language Models|Source - A Systematic Assessment of Syntactic Generalization in Neural Language Models]]
- [[../sources/Source - SyntaxGym|Source - SyntaxGym]]

## Source Identification
- Authors: Rebecca Marvin and Tal Linzen
- Title: "Targeted Syntactic Evaluation of Language Models"
- Year: 2018
- Source type: conference paper
- Publication: *Proceedings of EMNLP 2018*, pages 1192-1202

## Source Access
- Public source: [ACL Anthology page](https://aclanthology.org/D18-1151/)
