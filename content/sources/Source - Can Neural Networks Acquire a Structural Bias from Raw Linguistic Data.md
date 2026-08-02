---
title: Source - Can Neural Networks Acquire a Structural Bias from Raw Linguistic Data
type: source
status: active
updated: 2026-07-29
ingestion_depth: brief
tags:
  - source
  - brief
  - syntax
  - learnability
  - bert
  - inductive-bias
---

## Summary
Alex Warstadt and Samuel R. Bowman ask whether BERT can acquire a bias toward structural rather than linear generalizations purely from self-supervised pretraining on raw language data. Using poverty-of-the-stimulus-style test designs across subject-auxiliary inversion, reflexive binding, embedded-clause tense detection, and NPI licensing, they find structural generalization in three domains and a linear generalization in one. For WoLaLa, the paper matters because it turns a classic learnability dispute into an empirical question about what large pretrained models can acquire without explicit symbolic supervision.

## Strand Connections

- Primary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)
- Secondary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)

## WoLaLa Relevance
This source is important because it sharpens a recurrent WoLaLa question: when model success bears on claims about language learnability, what exactly has been learned and under what training conditions? Warstadt and Bowman do not argue that human acquisition and BERT pretraining are equivalent. Their claim is narrower and still significant: exposure to raw linguistic data plus a general pretraining objective can induce a structural preference in a system that was not explicitly built around hand-coded grammatical rules.

At the same time, the paper is useful because it refuses an all-or-nothing conclusion. The NPI result shows that the model does not simply become structure-sensitive across every phenomenon. That makes the paper a bridge between broad claims that raw data can explain everything and strong claims that neural learners remain incapable of acquiring grammar-relevant biases.

## Key Points
- The paper uses ambiguous training data and disambiguating held-out cases to test structural versus linear generalization directly.
- BERT generalizes structurally in subject-auxiliary inversion, reflexive binding, and embedded-clause tense detection.
- It fails to generalize structurally on the NPI task, showing that structural bias is uneven rather than automatic.
- The authors interpret the results as evidence that some grammar-relevant biases can emerge from raw-data pretraining.

## Limitation Or Open Question
The paper does not show that BERT learns syntax the way children do. The model sees vastly more data, uses a very different objective, and is evaluated after fine-tuning on template-generated tasks. The open question is how far this result should shift human-language-acquisition debates rather than only neural-model interpretation.

## Related Pages
- [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models Overview]]
- [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations Overview]]
- [[../sources/Source - Syntactic Structure from Deep Learning|Source - Syntactic Structure from Deep Learning]]
- [[../sources/Source - Three Models for the Description of Language|Source - Three Models for the Description of Language]]

## Source Identification
- Authors: Alex Warstadt and Samuel R. Bowman
- Title: *Can neural networks acquire a structural bias from raw linguistic data?*
- Year: 2020
- Source type: conference paper
- Publication: *Proceedings of the 42nd Annual Conference of the Cognitive Science Society*, pages 1736-1742
- Publication note: the local repository copy corresponds to the arXiv/CogSci conference version

## Source Access
- Public source: [arXiv abstract page](https://arxiv.org/abs/2007.06761)
