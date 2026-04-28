---
title: Source - A Structural Probe for Finding Syntax in Word Representations
type: source
status: active
updated: 2026-04-23
tags:
  - source
  - probing
  - syntax
  - bert
  - elmo
---

## Summary
Hewitt and Manning propose a structural probe that tests whether dependency tree structure is embedded in a linear transformation of contextual word representation space. They report evidence that ELMo and BERT representations contain parse-tree geometry better than several baselines, with useful structure recoverable in a relatively low-rank subspace.

## Key Points
- Source fact: the probe learns a linear transformation under which squared L2 distance between word vectors approximates dependency-tree distance.
- Source fact: a related norm probe tests whether squared vector norm approximates parse-tree depth.
- Source fact: the authors evaluate ELMo and BERT on Penn Treebank / Stanford Dependencies and compare against baselines including linear-chain, noncontextual ELMo0, decay contextualization, and a random BiLSTM projection baseline.
- Source fact: BERT-large layers perform best among the reported models, followed by BERT-base and ELMo, while contextualized baselines perform worse.
- Source fact: increasing the transformed dimensionality beyond roughly 64 or 128 gives little further gain in their rank analysis.
- Source fact: the authors explicitly limit the claim: the probe tests a strict geometric hypothesis about parse-tree distances and depths, not syntactic knowledge in every possible sense.

## Details
The central hypothesis is that syntax is represented as geometry: all pairs of words in a sentence should have vector distances corresponding to their syntactic tree distances. The resulting distances can be decoded into minimum spanning trees and evaluated with undirected unlabeled attachment score, while rank experiments estimate how compactly syntax is represented.

The paper's value for the wiki is that it gives a more structured alternative to ordinary classifier probes. It still uses supervision, but its learned object is constrained: a linear transformation inducing distances and norms.

## Synthesis / Interpretation
This source supports a cautious claim that BERT and ELMo contain extractable syntactic geometry. It does not by itself prove that the models use this geometry causally in downstream predictions.

Within `neural_nlp_probing`, this page is the clearest structured-geometry source. It remains a probing-style source rather than a mechanistic-interpretability page because the evidence comes from constrained readout, not identified causal circuits.

## Related Pages
- [[../concepts/Structural Probes|Structural Probes]]
- [[../concepts/Representation Geometry|Representation Geometry]]
- [[../concepts/Linguistic Knowledge in BERT|Linguistic Knowledge in BERT]]
- [[../analyses/What Probing Evidence Can Support|What Probing Evidence Can Support]]
- [[../overviews/Neural NLP Probing Overview|Neural NLP Probing Overview]]

## Source Identification
- Authors: John Hewitt and Christopher D. Manning
- Title: *A Structural Probe for Finding Syntax in Word Representations*

## Open Questions
- How should the wiki compare structural probes with edge probing and sentence-level probing tasks?
- Are low-rank syntactic subspaces stable across architectures, datasets, and languages?
