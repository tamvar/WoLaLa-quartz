---
title: Source - It's Not Greek to mBERT
type: source
status: active
updated: 2026-07-28
ingestion_depth: brief
tags:
  - source
  - brief
  - mbert
  - multilingual
  - translation
  - probing
---

## Summary
Hila Gonen, Shauli Ravfogel, Yanai Elazar, and Yoav Goldberg show that multilingual BERT contains substantial word-level translation information even without fine-tuning, and they use this result to argue that multilingual representations mix language-specific and more language-neutral components. For WoLaLa, the paper matters as a clean bridge between multilingual transfer claims and representation analysis: it asks not merely whether mBERT works across languages, but what kind of cross-lingual information is encoded and how recoverable it is.

## Strand Connections

- Primary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)
- Secondary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)

## WoLaLa Relevance
This source is valuable because it narrows multilingual claims into a precise representational question. Recoverable translation information is stronger than superficial lexical overlap, but weaker than a full theory of cross-lingual semantics. That makes the paper a useful control against both overclaiming and underclaiming about multilingual BERT.

## Key Points
- The paper exposes word-level translation ability in mBERT without task-specific fine-tuning.
- It argues that multilingual representations include both language-identity information and cross-lingual components.
- Translation information appears to be partly non-linear and only partly linearly accessible.
- The source is a good bridge from multilingual performance to representation structure.

## Limitation Or Open Question
Word-level translation recoverability does not settle whether mBERT shares deeper structural or semantic organization across languages. The open question is how far these representational regularities extend beyond lexical correspondence.

## Related Pages
- [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models Overview]]
- [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations Overview]]
- [[../sources/Source - How Multilingual Is Multilingual BERT|Source - How Multilingual Is Multilingual BERT]]
- [[../sources/Source - BERT|Source - BERT]]

## Source Identification
- Authors: Hila Gonen, Shauli Ravfogel, Yanai Elazar, and Yoav Goldberg
- Title: "It's not Greek to mBERT: Inducing Word-Level Translations from Multilingual BERT"
- Year: 2020
- Source type: workshop paper
- Publication: BlackboxNLP 2020

## Source Access
- Public source: [ACL Anthology page](https://aclanthology.org/2020.blackboxnlp-1.5/)
- DOI / publisher: [arXiv abstract page](https://arxiv.org/abs/2010.08275)
