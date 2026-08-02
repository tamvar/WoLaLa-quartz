---
title: Source - Learning Semantic Correspondences with Less Supervision
type: source
status: active
updated: 2026-07-29
ingestion_depth: brief
tags:
  - source
  - brief
  - grounded-language
  - acquisition
  - semantics
  - weak-supervision
---

## Summary
Percy Liang, Michael I. Jordan, and Dan Klein study grounded language acquisition under much weaker supervision than standard sentence-to-meaning datasets. Their model jointly segments text, identifies relevant facts in a structured world state, and aligns utterances with grounded meanings. For WoLaLa, the source matters because it gives a concrete computational version of the idea that semantic learning can proceed from noisy world-linked evidence rather than only from fully annotated logical forms.

## Strand Connections

- Primary: [[../overviews/Cultural, Cognitive, and SSH Perspectives Overview|Cultural, Cognitive, and SSH Perspectives]] (strand 5)
- Secondary: [[../overviews/Meaning, Reference, and Distributional Language Overview|Meaning, Reference, and Distributional Language]] (strand 3)

## WoLaLa Relevance
This source primarily supports [[../overviews/Cultural, Cognitive, and SSH Perspectives Overview|Cultural, Cognitive, and SSH Perspectives]] and secondarily [[../overviews/Meaning, Reference, and Distributional Language Overview|Meaning, Reference, and Distributional Language]]. It is useful because it links language learning to grounded world structure while explicitly reducing supervision. That makes it a good bridge between cognitive questions about acquisition and semantic questions about how text can come to align with nonlinguistic states of affairs.

## Limitation Or Open Question
The domains in the paper are structured and relatively bounded, so the work does not show how far weakly supervised grounding scales to open-ended natural language. The open question is how much of the apparent success comes from general acquisition principles and how much from the constrained record-text settings.

## Related Pages
- [[../overviews/Cultural, Cognitive, and SSH Perspectives Overview|Cultural, Cognitive, and SSH Perspectives Overview]]
- [[../overviews/Meaning, Reference, and Distributional Language Overview|Meaning, Reference, and Distributional Language Overview]]
- [[../sources/Source - A Probabilistic Model of Syntactic and Semantic Acquisition|Source - A Probabilistic Model of Syntactic and Semantic Acquisition]]
- [[../sources/Source - From Word Models to World Models|Source - From Word Models to World Models]]

## Source Identification
- Authors: Percy Liang, Michael I. Jordan, and Dan Klein
- Title: *Learning Semantic Correspondences with Less Supervision*
- Year: 2009
- Source type: conference paper
- Publication: *Proceedings of ACL-IJCNLP 2009*

## Source Access
- Public source: [ACL Anthology page](https://aclanthology.org/P09-1011/)
