---
title: Source - Assessing BERT's Syntactic Abilities
type: source
status: active
updated: 2026-07-27
ingestion_depth: brief
tags:
  - source
  - brief
  - bert
  - syntax
  - evaluation
  - probing
---

## Summary
Goldberg adapts earlier syntax-sensitive evaluation setups to BERT's masked-token setting and finds that the pretrained model performs surprisingly well on subject-verb agreement and reflexive-anaphora tests, including in "colorless green ideas" settings that reduce semantic cueing. For WoLaLa, the paper is useful because it shows that transformer architectures can capture substantial syntactic regularities even without explicit sequential recurrence, while still leaving open what kind of linguistic knowledge this performance reflects.

## Strand Connections

- Primary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)
- Secondary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)

## WoLaLa Relevance
This paper matters because it became one of the early results that made strong anti-transformer skepticism harder to maintain. At the same time, it is still an evaluation paper, not a full theory of what BERT represents. That combination makes it a good bridge source between competence claims and methodological caution.

## Key Points
- The paper adapts syntax-sensitive evaluation to BERT's bidirectional masked-word setup.
- BERT performs well on several controlled agreement and reflexive tests.
- Good results in semantically degraded settings suggest that performance is not only driven by lexical-semantic shortcuts.
- The source gives evidence of substantial syntactic sensitivity without resolving deeper questions about explanation.

## Related Pages
- [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models Overview]]
- [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations Overview]]
- [[../overviews/Neural NLP Probing Overview|Neural NLP Probing Overview]]
- [[../sources/Source - What Does BERT Learn About the Structure of Language|Source - What Does BERT Learn About the Structure of Language]]

## Source Identification
- Author: Yoav Goldberg
- Title: "Assessing BERT's Syntactic Abilities"
- Year: 2019
- Source type: preprint
- Publication context: arXiv `1901.05287`

## Source Access
- Public source: [arXiv abstract page](https://arxiv.org/abs/1901.05287)
