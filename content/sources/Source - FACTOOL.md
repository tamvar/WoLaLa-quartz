---
title: Source - FACTOOL
type: source
status: active
updated: 2026-07-28
ingestion_depth: brief
tags:
  - source
  - brief
  - evaluation
  - factuality
  - methodology
  - language-models
---

## Summary
FacTool proposes a tool-augmented framework for checking factuality in generative-model outputs across several distinct task types, including knowledge-based question answering, code generation, math, and scientific literature review. Instead of assuming that the claim to be checked or the relevant evidence is already given, the system tries to derive claims, retrieve evidence, and judge factuality in a more end-to-end way. For WoLaLa, the paper matters because it turns factuality evaluation into a concrete methodological problem rather than a vague complaint about hallucination.

## Strand Connections

- Primary: [[../overviews/Applications and Best Practices Overview|Applications and Best Practices]] (strand 6)
- Secondary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)

## WoLaLa Relevance
This source is useful because it sits at the point where application quality, evaluation design, and epistemic caution meet. It treats factuality checking as a language-centered task with domain variation, long outputs, and often missing evidence, which makes it more realistic than narrow benchmark settings.

## Key Points
- The paper argues that factuality detection for generative AI should work across multiple task and domain settings rather than only one benchmark.
- FacTool decomposes the problem into claim extraction, evidence retrieval, and factuality judgment.
- The framework is designed for settings where supporting evidence is not already packaged with the generated output.
- Its scientific-literature-review case is especially relevant for WoLaLa because it speaks directly to scholarly use and hallucinated citation risk.

## Limitation Or Open Question
The framework still depends on external tools and retrieval quality, so success does not mean that factuality has been solved in a domain-independent way. A live question is how well such systems transfer to linguistically subtle claims where evidence retrieval is itself ambiguous.

## Related Pages
- [[../overviews/Applications and Best Practices Overview|Applications and Best Practices Overview]]
- [[../sources/Source - Evaluating Factual Consistency of Summaries with Large Language Models|Source - Evaluating Factual Consistency of Summaries with Large Language Models]]
- [[../sources/Source - A Survey on Evaluation of Large Language Models|Source - A Survey on Evaluation of Large Language Models]]
- [[../sources/Source - Speak, Memory|Source - Speak, Memory]]

## Source Identification
- Authors: I-Chun Chern, Steffi Chern, Shiqi Chen, Weizhe Yuan, Kehua Feng, Chunting Zhou, Junxian He, Graham Neubig, and Pengfei Liu
- Title: "FacTool: Factuality Detection in Generative AI -- A Tool Augmented Framework for Multi-Task and Multi-Domain Scenarios"
- Year: 2023
- Source type: conference paper / preprint
- Publication context: EMNLP 2023 Findings; arXiv `2307.13528`

## Source Access
- Public source: [arXiv abstract page](https://arxiv.org/abs/2307.13528)
- DOI / publisher: [OpenReview page](https://openreview.net/forum?id=jolYuxpVn1)
