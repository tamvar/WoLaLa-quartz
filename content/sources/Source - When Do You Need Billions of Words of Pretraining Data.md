---
title: Source - When Do You Need Billions of Words of Pretraining Data
type: source
status: active
updated: 2026-07-28
ingestion_depth: brief
tags:
  - source
  - brief
  - scaling
  - pretraining-data
  - evaluation
  - syntax
---

## Summary
Yian Zhang, Alex Warstadt, Haau-Sing Li, and Samuel Bowman compare RoBERTa-style models pretrained on 1M to 30B words and show that many syntactic and semantic features stabilize with far less data than is needed for strong commonsense knowledge and downstream NLU performance. For WoLaLa, the paper matters because it disaggregates the effects of scale: more data does not improve all capacities equally, and linguistic-feature encoding is not the same thing as benchmark-level language understanding.

## Strand Connections

- Primary: [[../overviews/Applications and Best Practices Overview|Applications and Best Practices]] (strand 6)
- Secondary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)

## WoLaLa Relevance
This source is especially helpful for slowing down simplistic scaling narratives. It suggests that models can acquire a large amount of linguistically probed structure with comparatively modest pretraining data, while other skills that drive downstream `understanding` benchmarks require much more. That distinction is central to several WoLaLa disputes.

## Key Points
- The paper compares learning curves across probing, BLiMP, LAMA, and SuperGLUE-style evaluations.
- Many probed syntactic and semantic features stabilize around 10M to 100M words.
- Factual knowledge and downstream NLU tasks continue benefiting from much larger pretraining volumes.
- Linguistic feature encoding and benchmark-level task performance are therefore partly separable.

## Limitation Or Open Question
The paper shows that scale helps different capacities differently, but it does not fully specify what the larger-data gains beyond linguistic-feature encoding consist in. That unresolved remainder is exactly what makes the source valuable for WoLaLa.

## Related Pages
- [[../overviews/Applications and Best Practices Overview|Applications and Best Practices Overview]]
- [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models Overview]]
- [[../sources/Source - BERT|Source - BERT]]
- [[../sources/Source - Language Models are Few-Shot Learners|Source - Language Models are Few-Shot Learners]]

## Source Identification
- Authors: Yian Zhang, Alex Warstadt, Haau-Sing Li, and Samuel R. Bowman
- Title: "When Do You Need Billions of Words of Pretraining Data?"
- Year: 2021
- Source type: conference paper
- Publication: ACL-IJCNLP 2021

## Source Access
- Public source: [ACL Anthology page](https://aclanthology.org/2021.acl-long.90/)
- DOI / publisher: [DOI landing page](https://doi.org/10.18653/v1/2021.acl-long.90)
