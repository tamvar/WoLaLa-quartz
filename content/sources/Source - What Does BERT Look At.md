---
title: Source - What Does BERT Look At?
type: source
status: active
updated: 2026-07-26
ingestion_depth: brief
tags:
  - source
  - brief
  - bert
  - attention
  - analysis
---

## Summary
Kevin Clark, Urvashi Khandelwal, Omer Levy, and Christopher D. Manning analyze BERT's attention patterns directly rather than through probes or output behavior alone. They show that some heads display interpretable regularities, including next-token, delimiter, and syntactic-style attention patterns, while the overall picture remains heterogeneous. For WoLaLa, the paper matters as an intermediate case between broad probing claims and stronger mechanistic explanation: attention patterns are more concrete than flexible readout probes, but they still do not by themselves amount to a full theory of linguistic processing.

## Strand Connections

- Primary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)
- Secondary: [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering]] (strand 7)

## WoLaLa Relevance
This source primarily supports [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] and secondarily [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering]]. It is useful because it adds a more structure-aware lens on what BERT is doing without pretending that visible attention alone settles explanatory questions. The paper helps WoLaLa keep distinct three things that are often blurred together: linguistic competence, diagnostic interpretability, and mechanistic explanation.

## Limitation Or Open Question
Attention patterns are suggestive but not automatically causal. The open question is how much linguistic significance should be granted to interpretable heads once intervention-based evidence rather than descriptive analysis becomes the standard.

## Related Pages
- [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations Overview]]
- [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering Overview]]
- [[../sources/Source - In-context Learning and Induction Heads|Source - In-context Learning and Induction Heads]]

## Source Identification
- Authors: Kevin Clark, Urvashi Khandelwal, Omer Levy, and Christopher D. Manning
- Title: *What Does BERT Look At? An Analysis of BERT's Attention*
- Year: 2019
- Source type: conference paper

