---
title: Source - Learning Word Vectors for 157 Languages
type: source
status: active
updated: 2026-07-28
ingestion_depth: brief
tags:
  - source
  - brief
  - multilingual
  - word-vectors
  - fasttext
  - data
---

## Summary
Edouard Grave and colleagues describe the construction of large-scale fastText-style word vectors for 157 languages using Wikipedia and filtered Common Crawl data. The paper matters for WoLaLa because it provides a pre-LLM multilingual baseline for what broad language coverage, cross-lingual resource release, and large-scale lexical representation work looked like before today's foundation-model rhetoric. It is especially useful for separating multilingual lexical coverage from stronger claims about multilingual understanding.

## Strand Connections

- Primary: [[../overviews/Applications and Best Practices Overview|Applications and Best Practices]] (strand 6)
- Secondary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)

## WoLaLa Relevance
The paper's importance is partly infrastructural and partly conceptual. It shows how multilingual representation work depended on corpus scale, language identification, and data quality long before current LLMs. It also reminds us that good multilingual performance can mean robust lexical geometry and coverage, not yet deep multilingual reasoning or theory-level linguistic adequacy.

## Key Points
- The authors train high-quality pretrained word vectors for 157 languages from Wikipedia and Common Crawl.
- The work expands multilingual NLP by emphasizing broad release, evaluation datasets, and preprocessing quality.
- The representations are lexical and distributional, not sentence-level or task-general in the modern LLM sense.
- The source is useful as a baseline for later multilingual encoder and LLM claims.

## Limitation Or Open Question
Strong lexical vectors do not by themselves tell us how far a system can go on syntax, semantics, translation, or cross-lingual reasoning. The paper is best read as a broad multilingual lexical-resource anchor, not as a general theory of multilingual competence.

## Related Pages
- [[../overviews/Applications and Best Practices Overview|Applications and Best Practices Overview]]
- [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models Overview]]
- [[../sources/Source - How Multilingual Is Multilingual BERT|Source - How Multilingual Is Multilingual BERT]]
- [[../sources/Source - Unsupervised Cross-lingual Representation Learning at Scale|Source - Unsupervised Cross-lingual Representation Learning at Scale]]

## Source Identification
- Authors: Edouard Grave, Piotr Bojanowski, Prakhar Gupta, Armand Joulin, and Tomas Mikolov
- Title: "Learning Word Vectors for 157 Languages"
- Year: 2018
- Source type: conference paper
- Publication: LREC 2018

## Source Access
- Public source: [ACL Anthology page](https://aclanthology.org/L18-1550/)
- DOI / publisher: [arXiv abstract page](https://arxiv.org/abs/1802.06893)
