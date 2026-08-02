---
title: Source - The Language Interpretability Tool
type: source
status: active
updated: 2026-07-29
ingestion_depth: brief
tags:
  - source
  - brief
  - interpretability
  - evaluation
  - tooling
  - nlp
---

## Summary
Ian Tenney, James Wexler, Jasmijn Bastings, Tolga Bolukbasi, Andy Coenen, Sebastian Gehrmann, Ellen Jiang, Mahima Pushkarna, Carey Radebaugh, Emily Reif, and Ann Yuan present LIT, an interactive browser-based environment for inspecting NLP models through local explanations, aggregate comparisons, and counterfactual edits. For WoLaLa, the paper matters because it treats model understanding as a workflow problem: evidence about behavior often becomes clearer when researchers can inspect failures, perturbations, and example slices in one place rather than relying on a single static metric.

## Strand Connections

- Primary: [[../overviews/Applications and Best Practices Overview|Applications and Best Practices]] (strand 6)
- Secondary: [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering]] (strand 7)

## WoLaLa Relevance
This source primarily supports [[../overviews/Applications and Best Practices Overview|Applications and Best Practices]] and secondarily [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering]]. It is useful as a methodological bridge between evaluation and interpretability because it shows how counterfactual testing, error slicing, and local explanation can be combined in ordinary model-inspection practice. That matters for WoLaLa because many disputes about competence and explanation depend as much on how we interrogate models as on what benchmark number they reach.

## Limitation Or Open Question
LIT is a tool paper, not a theory of explanation. It improves researchers' ability to inspect behavior, but it does not by itself resolve which interpretability methods are epistemically strongest or which observed patterns support causal conclusions.

## Related Pages
- [[../overviews/Applications and Best Practices Overview|Applications and Best Practices Overview]]
- [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering Overview]]
- [[../sources/Source - A Survey on Evaluation of Large Language Models|Source - A Survey on Evaluation of Large Language Models]]
- [[../sources/Source - Do Models Explain Themselves|Source - Do Models Explain Themselves?]]

## Source Identification
- Authors: Ian Tenney, James Wexler, Jasmijn Bastings, Tolga Bolukbasi, Andy Coenen, Sebastian Gehrmann, Ellen Jiang, Mahima Pushkarna, Carey Radebaugh, Emily Reif, and Ann Yuan
- Title: *The Language Interpretability Tool: Extensible, Interactive Visualizations and Analysis for NLP Models*
- Year: 2020
- Source type: system demonstration paper
- Publication: *Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing: System Demonstrations*

## Source Access
- Public source: [ACL Anthology page](https://aclanthology.org/2020.emnlp-demos.15/)
- DOI / publisher: [ACL Anthology proceedings record](https://doi.org/10.18653/v1/2020.emnlp-demos.15)
