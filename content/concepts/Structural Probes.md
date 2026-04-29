---
title: Structural Probes
type: concept
status: active
updated: 2026-04-23
tags:
  - concept
  - probing
  - syntax
---

## Summary
Structural probes are constrained probes that test whether linguistic structure, especially parse-tree structure, is recoverable from representation geometry. In Hewitt and Manning's formulation, a learned linear transformation makes vector distances and norms approximate dependency-tree distances and depths.

## Key Points
- Hewitt and Manning's distance probe learns a linear transformation where squared L2 distance approximates parse-tree distance.
- their norm probe tests whether squared vector norm approximates parse-tree depth.
- the method evaluates a specific geometric hypothesis, rather than broad syntactic competence.
- the paper reports stronger syntactic geometry in ELMo and BERT than in several baselines.

## Details
[[../sources/Source - A Structural Probe for Finding Syntax in Word Representations|Hewitt and Manning]] make the structural probe important by constraining what the probe can learn. Instead of training an arbitrary parser on top of representations, the method asks whether a simple transformation exposes a global tree-distance geometry already present in the representation space.

Limitations remain. The probe uses supervised parse data, and successful recovery still supports an extractability claim unless paired with evidence that the original model relies on the recovered structure.

This page belongs on the probing side of the wiki's cluster boundary. Even though the probe tests a structured hypothesis, it is still a readout method rather than a causal account of transformer circuits.

## Related Pages
- [[Probing Classifiers]]
- [[Representation Geometry]]
- [[Linguistic Knowledge in BERT]]
- [[../analyses/What Probing Evidence Can Support|What Probing Evidence Can Support]]

## Sources
- [[../sources/Source - A Structural Probe for Finding Syntax in Word Representations|Source - A Structural Probe for Finding Syntax in Word Representations]]

## Open Questions
- Are syntactic subspaces stable across model families and languages?
- How should structural probes be compared with attention-based parse extraction and edge probing?
