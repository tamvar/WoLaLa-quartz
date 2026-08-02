---
title: Source - Subword Language Modelling
type: source
status: active
updated: 2026-07-26
ingestion_depth: brief
tags:
  - source
  - brief
  - subword
  - tokenization
  - language-modeling
---

## Summary
Tomáš Mikolov, Ilya Sutskever, Anoop Deoras, Hai-Son Le, Stefan Kombrink, and Jan Černocký compare character-level and word-level language modeling and motivate intermediate subword strategies. For WoLaLa, the paper works as a historical source on a design problem that later became central for transformer-era language models: how should models segment language so that they preserve useful lexical and morphological structure without exploding vocabulary size?

## Strand Connections

- Primary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)
- Secondary: [[../overviews/Historical Perspectives on Language, Mind, and Modeling Overview|Historical Perspectives on Language, Mind, and Modeling]] (strand 9)

## WoLaLa Relevance
This source primarily supports [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] and secondarily [[../overviews/Historical Perspectives on Language, Mind, and Modeling Overview|Historical Perspectives on Language, Mind, and Modeling]]. It matters because it helps historicize tokenization as a genuine modeling choice rather than a housekeeping trick. The paper makes visible the tradeoffs among characters, words, and intermediate units that still shape how current models handle morphology, rare forms, and multilingual variation.

## Limitation Or Open Question
This is an early neural language-modeling source, so it predates transformers and the present scale regime. The open question is which of its segmentation lessons remain durable under modern architectures and large pretraining corpora.

## Related Pages
- [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations Overview]]
- [[../overviews/Historical Perspectives on Language, Mind, and Modeling Overview|Historical Perspectives on Language, Mind, and Modeling Overview]]
- [[../sources/Source - Neural Machine Translation of Rare Words with Subword Units|Source - Neural Machine Translation of Rare Words with Subword Units]]

## Source Identification
- Authors: Tomáš Mikolov, Ilya Sutskever, Anoop Deoras, Hai-Son Le, Stefan Kombrink, and Jan Černocký
- Title: *Subword Language Modelling with Neural Networks*
- Year: 2012
- Source type: workshop or conference paper

