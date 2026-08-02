---
title: Source - A Survey of Cross-lingual Word Embedding Models
type: source
status: active
updated: 2026-07-28
ingestion_depth: brief
tags:
  - source
  - brief
  - cross-lingual
  - embeddings
  - multilinguality
  - survey
---

## Summary
Sebastian Ruder, Ivan Vulić, and Anders Søgaard survey cross-lingual word embedding models as tools for multilingual meaning representation and cross-lingual transfer. The survey compares model families, supervision levels, data requirements, and evaluation methods, and emphasizes that many apparently different systems optimize very similar objectives. For WoLaLa, the source matters because it gives the multilingual and applications strands a compact map of how lexical meaning is aligned across languages and how such alignment is evaluated.

## Strand Connections

- Primary: [[../overviews/Applications and Best Practices Overview|Applications and Best Practices]] (strand 6)
- Secondary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)

## WoLaLa Relevance
This source is valuable as a multilingual-method survey. It clarifies what kinds of alignment resources, objectives, and evaluations underlie claims about cross-lingual semantic transfer.

## Key Points
- The survey gives a broad typology of cross-lingual embedding models and their supervision requirements.
- It emphasizes that many model differences reduce to data choice, objective choice, and optimization details.
- The paper treats both semantic similarity and transfer performance as important evaluation targets.
- It is especially relevant to low-resource and multilingual transfer questions.
- For WoLaLa, it helps anchor multilinguality in explicit methodological terms rather than in vague transfer rhetoric.

## Limitation Or Open Question
The survey predates contextual multilingual transformers and so belongs to an earlier phase of multilingual representation learning. Its value now is partly historical and partly methodological.

## Related Pages
- [[../overviews/Applications and Best Practices Overview|Applications and Best Practices Overview]]
- [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models Overview]]
- [[../sources/Source - How Multilingual Is Multilingual BERT|Source - How Multilingual Is Multilingual BERT]]
- [[../sources/Source - On the Multilingual Capabilities of Very Large-Scale English Language Models|Source - On the Multilingual Capabilities of Very Large-Scale English Language Models]]

## Source Identification
- Authors: Sebastian Ruder, Ivan Vulić, and Anders Søgaard
- Title: "A Survey of Cross-lingual Word Embedding Models"
- Year: 2019
- Source type: survey article
- Publication: *Journal of Artificial Intelligence Research* 65, 569-631
- Note on local version: the repository copy is an arXiv survey version.

## Source Access
- Public source: [arXiv abstract page](https://arxiv.org/abs/1706.04902)
