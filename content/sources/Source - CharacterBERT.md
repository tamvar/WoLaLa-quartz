---
title: Source - CharacterBERT
type: source
status: active
updated: 2026-07-29
ingestion_depth: brief
tags:
  - source
  - brief
  - bert
  - character-level
  - tokenization
  - domain-adaptation
---

## Summary
Hicham El Boukkouri, Olivier Ferret, Thomas Lavergne, Hiroshi Noji, Pierre Zweigenbaum, and Junichi Tsujii propose CharacterBERT, a BERT variant that removes fixed wordpiece vocabularies and instead represents whole words from characters using a Character-CNN module. For WoLaLa, the source matters because it makes tokenization a design choice rather than a hidden default and shows that open-vocabulary, word-level modeling can be practically valuable, especially in specialized domains.

## Strand Connections

- Primary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)
- Secondary: [[../overviews/Applications and Best Practices Overview|Applications and Best Practices]] (strand 6)

## WoLaLa Relevance
This source primarily supports [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] and secondarily [[../overviews/Applications and Best Practices Overview|Applications and Best Practices]]. It is useful because it tests whether BERT-like contextual modeling really requires wordpieces. That matters for competence claims about morphology, lexical coverage, and robustness, especially when models are moved into technical or domain-specific language where fixed vocabularies are often fragile.

## Limitation Or Open Question
CharacterBERT shows one promising alternative to wordpiece encoding, but it does not establish that character-derived word representations are generally superior across domains. The open question is when tokenization-free or tokenization-light designs produce deeper linguistic advantages rather than mainly practical robustness gains.

## Related Pages
- [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations Overview]]
- [[../overviews/Applications and Best Practices Overview|Applications and Best Practices Overview]]
- [[../sources/Source - CharBERT|Source - CharBERT]]
- [[../sources/Source - ByT5|Source - ByT5]]

## Source Identification
- Authors: Hicham El Boukkouri, Olivier Ferret, Thomas Lavergne, Hiroshi Noji, Pierre Zweigenbaum, and Junichi Tsujii
- Title: *CharacterBERT: Reconciling ELMo and BERT for Word-Level Open-Vocabulary Representations From Characters*
- Year: 2020
- Source type: research paper
- Publication context: arXiv preprint

## Source Access
- Public source: [arXiv abstract page](https://arxiv.org/abs/2010.10392)
