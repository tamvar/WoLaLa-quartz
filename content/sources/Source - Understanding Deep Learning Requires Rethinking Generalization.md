---
title: Source - Understanding Deep Learning Requires Rethinking Generalization
type: source
status: active
updated: 2026-07-29
ingestion_depth: brief
tags:
  - source
  - brief
  - generalization
  - deep-learning-theory
  - methodology
  - scaling
---

## Summary
Chiyuan Zhang, Samy Bengio, Moritz Hardt, Benjamin Recht, and Oriol Vinyals argue that standard explanations of why deep networks generalize are inadequate. Their key evidence is that large networks can fit random labels and even random noise, showing that capacity and explicit regularization do not explain practical generalization in the familiar way. For WoLaLa, the paper matters because it destabilizes easy stories about why large neural systems work and forces stronger caution when success is redescribed as understanding.

## Strand Connections

- Primary: [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering]] (strand 7)
- Secondary: [[../overviews/Historical Perspectives on Language, Mind, and Modeling Overview|Historical Perspectives on Language, Mind, and Modeling]] (strand 9)

## WoLaLa Relevance
This source primarily supports [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering]] and secondarily [[../overviews/Historical Perspectives on Language, Mind, and Modeling Overview|Historical Perspectives on Language, Mind, and Modeling]]. It is useful because it undercuts simple appeals to small train-test gaps as an explanation of deep-model success. For WoLaLa, that means language-model competence should not be interpreted through inherited generalization intuitions without asking what the model can memorize, interpolate, or fit for the wrong reasons.

## Limitation Or Open Question
The experiments are not language-specific, and the paper is more a challenge than a replacement theory. The open question is what account of generalization should replace the older one, especially for large language models trained on heterogeneous text corpora.

## Related Pages
- [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering Overview]]
- [[../overviews/Historical Perspectives on Language, Mind, and Modeling Overview|Historical Perspectives on Language, Mind, and Modeling Overview]]
- [[../sources/Source - The Bitter Lesson|Source - The Bitter Lesson]]
- [[../sources/Source - Scaling Language Models from Gopher|Source - Scaling Language Models from Gopher]]

## Source Identification
- Authors: Chiyuan Zhang, Samy Bengio, Moritz Hardt, Benjamin Recht, and Oriol Vinyals
- Title: *Understanding Deep Learning Requires Rethinking Generalization*
- Year: 2017
- Source type: research paper
- Publication context: arXiv preprint

## Source Access
- Public source: [arXiv abstract page](https://arxiv.org/abs/1611.03530)
