---
title: Source - Open Sesame
type: source
status: active
updated: 2026-07-29
ingestion_depth: brief
tags:
  - source
  - brief
  - bert
  - syntax
  - hierarchy
  - probing
---

## Summary
Yongjie Lin, Yi Chern Tan, and Robert Frank investigate whether BERT represents hierarchical rather than merely positional information. Their two studies suggest that lower BERT layers track linear position more strongly, while higher layers encode more hierarchy-sensitive structure, though not with uniformly human-like sharpness. For WoLaLa, the paper matters because it addresses one of the central BERT-era questions directly: does strong contextual performance reflect linguistically relevant hierarchical organization or only powerful sequence statistics?

## Strand Connections

- Primary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)
- Secondary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)

## WoLaLa Relevance
This source primarily supports [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] and secondarily [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]]. It is valuable because it tests a specifically linguistic distinction between linear order and hierarchical structure. The paper strengthens the case that BERT contains nontrivial structure-sensitive information, while also showing that this should not be inflated into a claim of fully human-like syntactic processing.

## Limitation Or Open Question
The authors find evidence for hierarchy-sensitive representation, but they also report weaker human-like sensitivity for reflexive-anaphora cases. The open question is how far such evidence supports genuine syntactic generalization rather than only partial structural correlates extractable from large-scale pretraining.

## Related Pages
- [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations Overview]]
- [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models Overview]]
- [[../overviews/Neural NLP Probing Overview|Neural NLP Probing Overview]]
- [[../sources/Source - A Primer in BERTology|Source - A Primer in BERTology]]
- [[../sources/Source - Assessing BERT's Syntactic Abilities|Source - Assessing BERT's Syntactic Abilities]]

## Source Identification
- Authors: Yongjie Lin, Yi Chern Tan, and Robert Frank
- Title: *Open Sesame: Getting Inside BERT's Linguistic Knowledge*
- Year: 2019
- Source type: workshop paper
- Publication: *Proceedings of the Second BlackboxNLP Workshop on Analyzing and Interpreting Neural Networks for NLP*

## Source Access
- Public source: [ACL Anthology page](https://aclanthology.org/W19-4825/)
