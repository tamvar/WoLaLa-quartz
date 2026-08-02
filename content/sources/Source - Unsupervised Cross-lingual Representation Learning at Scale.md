---
title: Source - Unsupervised Cross-lingual Representation Learning at Scale
type: source
status: active
updated: 2026-07-28
ingestion_depth: brief
tags:
  - source
  - brief
  - xlm-r
  - multilingual
  - scaling
  - transfer
---

## Summary
Alexis Conneau and colleagues present XLM-R, a multilingual masked language model trained on 100 languages and very large filtered Common Crawl data. The paper argues that scale can improve cross-lingual transfer substantially while also clarifying a core multilingual tradeoff: positive transfer across languages can come at the cost of capacity dilution. For WoLaLa, the source matters because it gives a strong multilingual scaling comparison point against both mBERT and later multilingual LLM claims.

## Strand Connections

- Primary: [[../overviews/Applications and Best Practices Overview|Applications and Best Practices]] (strand 6)
- Secondary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)

## WoLaLa Relevance
The paper is useful both as a multilingual resource milestone and as an evidential caution. It shows that multilingual scale can help low-resource languages, but it also insists that multilinguality is not free: capacity, resource imbalance, and transfer tradeoffs must be analyzed rather than assumed away.

## Key Points
- XLM-R scales multilingual masked-language-model pretraining to 100 languages and more than 2TB of Common Crawl text.
- The model substantially improves over mBERT and earlier XLM variants on multiple cross-lingual benchmarks.
- The paper identifies a central tradeoff between positive transfer and capacity dilution.
- It also argues that multilingual scaling need not always sacrifice monolingual performance.

## Limitation Or Open Question
Benchmark gains do not by themselves show that multilingual models have a unified cross-lingual semantics or theory-like grammatical abstraction. The paper is strongest as a multilingual transfer and scaling study, not as a philosophical or linguistic-resolution source.

## Related Pages
- [[../overviews/Applications and Best Practices Overview|Applications and Best Practices Overview]]
- [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations Overview]]
- [[../sources/Source - How Multilingual Is Multilingual BERT|Source - How Multilingual Is Multilingual BERT]]
- [[../sources/Source - It's Not Greek to mBERT|Source - It's Not Greek to mBERT]]
- [[../sources/Source - mT5|Source - mT5]]

## Source Identification
- Authors: Alexis Conneau, Kartikay Khandelwal, Naman Goyal, Vishrav Chaudhary, Guillaume Wenzek, Francisco Guzman, Edouard Grave, Myle Ott, Luke Zettlemoyer, and Veselin Stoyanov
- Title: "Unsupervised Cross-lingual Representation Learning at Scale"
- Year: 2020
- Source type: conference paper
- Publication: ACL 2020

## Source Access
- Public source: [ACL Anthology page](https://aclanthology.org/2020.acl-main.747/)
- DOI / publisher: [arXiv abstract page](https://arxiv.org/abs/1911.02116)
