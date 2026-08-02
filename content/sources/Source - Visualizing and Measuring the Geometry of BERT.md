---
title: Source - Visualizing and Measuring the Geometry of BERT
type: source
status: active
updated: 2026-07-29
ingestion_depth: brief
tags:
  - source
  - brief
  - bert
  - geometry
  - syntax
  - semantics
---

## Summary
Andy Coenen, Emily Reif, Ann Yuan, Been Kim, Adam Pearce, Fernanda Viégas, and Martin Wattenberg study how BERT's internal spaces organize linguistic information. They argue that BERT appears to separate semantic and syntactic information into partly distinct subspaces and that its token representations encode fine-grained sense structure. For WoLaLa, the source matters because it gives a more geometric and visualization-oriented account of linguistic structure than the standard probe literature alone.

## Strand Connections

- Primary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)
- Secondary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)

## WoLaLa Relevance
This source primarily supports [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] and secondarily [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]]. It is useful because it suggests that linguistic structure in BERT is not only recoverable by supervised probes but also reflected in the geometry of the representation space itself. That makes it a bridge between descriptive probing results and stronger claims about internally organized syntax-semantics structure.

## Limitation Or Open Question
The paper remains interpretive rather than decisively mechanistic. Discovering semantic and syntactic subspaces does not by itself show how those spaces are used during inference or whether they correspond to linguistically natural categories in a stable way across models.

## Related Pages
- [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations Overview]]
- [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models Overview]]
- [[../overviews/Neural NLP Probing Overview|Neural NLP Probing Overview]]
- [[../sources/Source - A Primer in BERTology|Source - A Primer in BERTology]]
- [[../sources/Source - Open Sesame|Source - Open Sesame]]

## Source Identification
- Authors: Andy Coenen, Emily Reif, Ann Yuan, Been Kim, Adam Pearce, Fernanda Viégas, and Martin Wattenberg
- Title: *Visualizing and Measuring the Geometry of BERT*
- Year: 2019
- Source type: research paper
- Publication context: arXiv preprint

## Source Access
- Public source: [arXiv abstract page](https://arxiv.org/abs/1906.02715)
