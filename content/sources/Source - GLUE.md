---
title: Source - GLUE
type: source
status: active
updated: 2026-07-28
ingestion_depth: brief
tags:
  - source
  - brief
  - evaluation
  - benchmark
  - nlu
  - methodology
---

## Summary
GLUE introduces the General Language Understanding Evaluation benchmark as a multi-task platform for assessing whether models can transfer across diverse natural-language-understanding tasks rather than excelling on only one narrow dataset. Its importance is not just that it became a famous leaderboard, but that it bundled ordinary task performance with a diagnostic set aimed at more linguistically interpretable analysis. For WoLaLa, GLUE is a historical methodological hinge between generic benchmark culture and more language-aware evaluation design.

## Strand Connections

- Primary: [[../overviews/Applications and Best Practices Overview|Applications and Best Practices]] (strand 6)
- Secondary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)

## WoLaLa Relevance
This source matters because it makes explicit a tension that still shapes WoLaLa-relevant evaluation: broad task coverage can drive progress, but aggregate benchmark success does not by itself reveal what a model knows about syntax, semantics, or reasoning. GLUE is therefore both an enabling benchmark and an early reminder that diagnostic linguistic analysis has to accompany leaderboard reporting.

## Key Points
- GLUE aims to evaluate cross-task generality rather than single-dataset specialization.
- It combines benchmark tasks with a diagnostic set for more fine-grained linguistic analysis.
- The paper shows that then-current transfer and multitask methods still left substantial room for improvement.
- Its framing helped turn benchmark suites into a central part of language-model evaluation culture.

## Limitation Or Open Question
GLUE is historically important, but it also exemplifies the limits of broad aggregate scores. A persistent question is how much such benchmarks reveal about genuine language understanding rather than transferable shortcut exploitation.

## Related Pages
- [[../overviews/Applications and Best Practices Overview|Applications and Best Practices Overview]]
- [[../sources/Source - SyntaxGym|Source - SyntaxGym]]
- [[../sources/Source - Targeted Syntactic Evaluation of Language Models|Source - Targeted Syntactic Evaluation of Language Models]]
- [[../sources/Source - A Systematic Assessment of Syntactic Generalization in Neural Language Models|Source - A Systematic Assessment of Syntactic Generalization in Neural Language Models]]

## Source Identification
- Authors: Alex Wang, Amanpreet Singh, Julian Michael, Felix Hill, Omer Levy, and Samuel R. Bowman
- Title: "GLUE: A Multi-Task Benchmark and Analysis Platform for Natural Language Understanding"
- Year: 2018
- Source type: conference paper
- Publication: *Proceedings of the 2018 EMNLP Workshop BlackboxNLP*

## Source Access
- Public source: [arXiv abstract page](https://arxiv.org/abs/1804.07461)
- DOI / publisher: [ACL Anthology page](https://aclanthology.org/W18-5446/)
