---
title: Source - A Primer in BERTology
type: source
status: active
updated: 2026-07-29
ingestion_depth: deep
tags:
  - source
  - deep
  - bert
  - probing
  - survey
  - interpretability
---

## Summary
Anna Rogers, Olga Kovaleva, and Anna Rumshisky survey what was known in 2020 about how BERT works, what kinds of linguistic information it appears to encode, where that information may be represented, and how the model had already been modified or compressed. For WoLaLa, the paper matters because it turns a scattered BERT-analysis literature into one organized methodological checkpoint: it shows both how much had been extracted from BERT and how much still depended on indirect evidence rather than settled explanation.

## Strand Connections

- Primary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)
- Secondary: [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering]] (strand 7)

## Key Points
- The paper synthesizes a broad early BERT-analysis literature rather than advancing one new probe or benchmark.
- It treats BERT as a model that clearly encodes useful linguistic information, but one whose internal organization remains only partly understood.
- The survey distinguishes questions about what knowledge BERT contains, where that knowledge is located, how pretraining creates it, and how later architectural changes affect it.
- It highlights compression, pruning, and architectural modification work as evidence that high performance does not by itself reveal which parts of the model are doing the important work.
- The paper is methodologically valuable because it repeatedly separates robust empirical findings from stronger causal or explanatory claims that the literature had not yet earned.

## Details
The survey organizes BERTology around several recurring questions. One is representational: which linguistic properties can be extracted from BERT's layers, heads, and token states? Another is architectural: how much of BERT's success depends on depth, self-attention patterns, pretraining objectives, or overparameterization? A third is practical: which modifications preserve performance, and which seem to damage the model's ability to support downstream transfer?

For WoLaLa, the paper is especially useful because it refuses to collapse these questions into a single success story. It collects evidence that BERT supports part-of-speech, syntax, word-sense, and other linguistically structured analyses, but it also emphasizes unresolved problems about explanation. A model can perform well, and a probe can recover useful information from it, without that immediately telling us what internal computational strategy the model relies on during ordinary use.

The survey also helps situate later LLM debates historically. Many contemporary arguments about probing, interpretability, and representation geometry were already visible in concentrated form in the BERT era. The paper therefore functions as a bridge between narrower sources such as [[../sources/Source - Open Sesame|Open Sesame]] and [[../sources/Source - Visualizing and Measuring the Geometry of BERT|Visualizing and Measuring the Geometry of BERT]], and broader questions about what counts as explanation in language-model analysis.

## Interpretation
This source should be read as a methodological map, not as a final verdict on what BERT knows. Its importance lies in showing that the field already had a substantial body of evidence about linguistic extractability and architectural sensitivity, while still lacking a comparably strong account of mechanism. That makes it an anchor for WoLaLa's distinction between competence evidence, diagnostic evidence, and genuine reverse engineering.

## WoLaLa Relevance
This source primarily supports [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] and secondarily [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering]]. It is especially useful for:

- giving the strand a compact survey-level account of the early BERT analysis literature;
- showing why strong probing and transfer results do not by themselves settle explanatory questions;
- connecting BERT-era analysis practice to later arguments about interpretability, compression, and architectural sufficiency.

## Limitation Or Open Question
Because the survey reflects the state of the literature in 2020, it necessarily stops before later large-model and mechanistic-interpretability developments. An open question for WoLaLa is how much of the BERTology picture generalizes to current LLMs and how much depends on a narrower encoder-only pretraining regime.

## Related Pages
- [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations Overview]]
- [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering Overview]]
- [[../overviews/Neural NLP Probing Overview|Neural NLP Probing Overview]]
- [[../sources/Source - BERT|Source - BERT]]
- [[../sources/Source - Open Sesame|Source - Open Sesame]]
- [[../sources/Source - Visualizing and Measuring the Geometry of BERT|Source - Visualizing and Measuring the Geometry of BERT]]

## Source Identification
- Authors: Anna Rogers, Olga Kovaleva, and Anna Rumshisky
- Title: *A Primer in BERTology: What We Know About How BERT Works*
- Year: 2020
- Source type: survey article
- Publication: *Transactions of the Association for Computational Linguistics* 8

## Source Access
- Public source: [ACL Anthology page](https://aclanthology.org/2020.tacl-1.54/)
- DOI / publisher: [TACL / MIT Press page](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00349/96482/A-Primer-in-BERTology-What-We-Know-About-How-BERT)
