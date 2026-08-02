---
title: Source - Neural Network Acceptability Judgments
type: source
status: active
updated: 2026-07-29
ingestion_depth: brief
tags:
  - source
  - brief
  - syntax
  - acceptability
  - evaluation
  - cola
---

## Summary
Alex Warstadt, Amanpreet Singh, and Samuel R. Bowman introduce the Corpus of Linguistic Acceptability (CoLA) and use it to ask whether neural networks can perform linguistically meaningful grammaticality judgments. Their models beat earlier unsupervised baselines, but remain far below human performance and do especially poorly on many nonlocal grammatical dependencies. For WoLaLa, the paper matters because it turns one of generative linguistics' classic evidence types into a machine-readable evaluation task without pretending that benchmark success would settle the underlying theory question.

## Strand Connections

- Primary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)
- Secondary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)

## WoLaLa Relevance
This source is useful because it makes acceptability judgment a common meeting point between linguistic theory and model evaluation. CoLA is not just another NLP benchmark: its data comes from published linguistics examples, and its target behavior is closely tied to how theorists have long argued about grammatical competence. That makes the paper a major bridge between formal linguistic evidence and neural evaluation practice.

The paper is also restrained in the right way. Its models show some real grammatical generalization, especially on simpler word-order and argument-structure patterns, but they remain weak on harder phenomena. That matters for WoLaLa because it blocks two easy overreactions at once: the claim that neural models obviously lack grammar, and the claim that any above-baseline performance on CoLA would amount to human-like linguistic competence.

## Key Points
- The paper introduces CoLA as a large acceptability dataset sourced from linguistics literature.
- It tests whether neural models can reproduce expert grammaticality judgments.
- Models outperform earlier unsupervised baselines but stay far below human performance.
- Error analysis shows better learning of local order and argument structure than of longer-distance dependencies.

## Limitation Or Open Question
CoLA is still a Boolean acceptability task, and performance on it does not by itself capture full syntactic competence, semantic interpretation, or actual sentence processing. The open question is how acceptability evidence should be combined with targeted minimal-pair tests, surprisal-based measures, and internal analyses.

## Related Pages
- [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models Overview]]
- [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations Overview]]
- [[../sources/Source - Targeted Syntactic Evaluation of Language Models|Source - Targeted Syntactic Evaluation of Language Models]]
- [[../sources/Source - Investigating BERT's Knowledge of Language|Source - Investigating BERT's Knowledge of Language]]

## Source Identification
- Authors: Alex Warstadt, Amanpreet Singh, and Samuel R. Bowman
- Title: *Neural Network Acceptability Judgments*
- Year: 2019
- Source type: journal article
- Publication: *Transactions of the Association for Computational Linguistics* 7, 625-641
- DOI: `10.1162/tacl_a_00290`

## Source Access
- Public source: [DOI landing page](https://doi.org/10.1162/tacl_a_00290)
