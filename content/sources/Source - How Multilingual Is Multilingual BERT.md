---
title: Source - How Multilingual Is Multilingual BERT
type: source
status: active
updated: 2026-07-28
ingestion_depth: brief
tags:
  - source
  - brief
  - multilingual-bert
  - cross-lingual-transfer
  - competence
  - probing
---

## Summary
Telmo Pires, Eva Schlinger, and Dan Garrette study why Multilingual BERT supports surprisingly strong zero-shot cross-lingual transfer. Their experiments show that M-BERT builds genuinely multilingual representations, but that transfer is uneven and depends strongly on typological similarity and other language-pair factors. For WoLaLa, the paper matters because it is a clean early bridge between multilingual competence claims and explicit probing evidence.

## Strand Connections

- Primary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)
- Secondary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)

## WoLaLa Relevance
This source is useful because it turns `multilinguality` into a testable representational question rather than treating multilingual transfer as a black-box success story.

## Key Points
- The paper shows that M-BERT supports substantial zero-shot cross-lingual transfer.
- It argues that the model learns genuinely multilingual representations rather than relying only on lexical overlap.
- Transfer works better for typologically similar languages and reveals systematic weaknesses for some language pairs.
- The source is an early multilingual probing anchor rather than a general benchmark paper.
- For WoLaLa, it helps connect multilingual competence claims to explicit evidence about representation sharing and its limits.

## Limitation Or Open Question
The paper focuses on an early multilingual transformer and does not settle how later larger multilingual systems change the picture. Its main value is to establish the question clearly and empirically.

## Related Pages
- [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations Overview]]
- [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models Overview]]
- [[../sources/Source - Finding Universal Grammatical Relations in Multilingual BERT|Source - Finding Universal Grammatical Relations in Multilingual BERT]]
- [[../sources/Source - A Survey of Cross-lingual Word Embedding Models|Source - A Survey of Cross-lingual Word Embedding Models]]

## Source Identification
- Authors: Telmo Pires, Eva Schlinger, and Dan Garrette
- Title: "How multilingual is Multilingual BERT?"
- Year: 2019
- Source type: conference paper
- Publication: *Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics*, 4996-5001

## Source Access
- Public source: [ACL Anthology page](https://aclanthology.org/P19-1493/)
