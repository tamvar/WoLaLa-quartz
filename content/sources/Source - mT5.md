---
title: Source - mT5
type: source
status: active
updated: 2026-07-28
ingestion_depth: brief
tags:
  - source
  - brief
  - mt5
  - multilingual
  - text-to-text
  - transfer
---

## Summary
Linting Xue and colleagues introduce mT5 as a multilingual extension of the T5 text-to-text framework, pretrained on Common Crawl data in 101 languages. The paper matters for WoLaLa because it shows how a generative text-to-text model can be scaled into the multilingual setting while preserving a single task format across many benchmarks. It also foregrounds a concrete multilingual failure mode, `accidental translation`, which helps make cross-lingual competence more analytically precise than simple success/failure averages.

## Strand Connections

- Primary: [[../overviews/Applications and Best Practices Overview|Applications and Best Practices]] (strand 6)
- Secondary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)

## WoLaLa Relevance
This source helps connect multilingual model building to methodological caution. mT5 is not just another larger multilingual benchmark result. It shows that multilingual generation raises specific control problems about language selection, transfer, and evaluation. Those issues matter whenever broad claims are made about `multilingual understanding` from a single model family.

## Key Points
- mT5 extends the T5 text-to-text framework to 101 languages using multilingual Common Crawl data.
- The model keeps a unified generative task format rather than separate task-specific heads.
- The paper identifies accidental translation as a recurring multilingual failure mode in zero-shot generation.
- The source is useful for comparing multilingual encoder-style and encoder-decoder-style competence claims.

## Limitation Or Open Question
The paper is strongest on multilingual benchmark performance and model design, but it leaves open how multilingual gains should be interpreted theoretically: shared competence, partial alignment, and language-resource asymmetry are not the same phenomenon.

## Related Pages
- [[../overviews/Applications and Best Practices Overview|Applications and Best Practices Overview]]
- [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations Overview]]
- [[../sources/Source - How Multilingual Is Multilingual BERT|Source - How Multilingual Is Multilingual BERT]]
- [[../sources/Source - On the Multilingual Capabilities of Very Large-Scale English Language Models|Source - On the Multilingual Capabilities of Very Large-Scale English Language Models]]

## Source Identification
- Authors: Linting Xue, Noah Constant, Adam Roberts, Mihir Kale, Rami Al-Rfou, Aditya Siddhant, Aditya Barua, and Colin Raffel
- Title: "mT5: A Massively Multilingual Pre-trained Text-to-Text Transformer"
- Year: 2021
- Source type: conference paper
- Publication: NAACL-HLT 2021

## Source Access
- Public source: [arXiv abstract page](https://arxiv.org/abs/2010.11934)
- DOI / publisher: [ACL Anthology page](https://aclanthology.org/2021.naacl-main.41/)
