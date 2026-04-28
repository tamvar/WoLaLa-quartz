---
title: Representation Geometry
type: concept
status: active
updated: 2026-04-23
tags:
  - concept
  - representations
  - geometry
  - probing
---

## Summary
Representation geometry refers to claims about what structure is encoded in distances, norms, directions, or subspaces of neural representations. In the present source set, the clearest example is the structural probe claim that parse-tree structure is recoverable from transformed vector distances and norms.

## Key Points
- Source fact: Hewitt and Manning test whether dependency-tree distances and depths correspond to squared L2 distances and norms after a learned linear transformation.
- Source fact: their rank analysis suggests syntactic structure can be recovered from a lower-dimensional transformed space.
- Source fact: Jawahar et al. use TPDN approximation to test whether BERT representations are better approximated by tree-like role schemes than by several linear or bag-of-words alternatives.
- Synthesis: geometry-based evidence is more structured than ordinary classification accuracy, but still requires caution about causal use.

## Details
Geometry-based probing asks not merely whether a label can be predicted, but whether a representation space has a form compatible with a proposed structure. [[../sources/Source - A Structural Probe for Finding Syntax in Word Representations|Hewitt and Manning]] make this concrete with parse distance and parse depth, while [[../sources/Source - What Does BERT Learn About the Structure of Language|Jawahar et al.]] extend the idea to tree-like compositional role schemes through TPDN approximation.

These results are more structured than ordinary probe accuracy, but they still belong to the probing cluster's evidence style: recoverable geometry and approximation quality, not mechanistic identification of circuits.

## Related Pages
- [[Structural Probes]]
- [[Linguistic Knowledge in BERT]]
- [[Probing Classifiers]]
- [[../analyses/What Probing Evidence Can Support|What Probing Evidence Can Support]]

## Sources
- [[../sources/Source - A Structural Probe for Finding Syntax in Word Representations|Source - A Structural Probe for Finding Syntax in Word Representations]]
- [[../sources/Source - What Does BERT Learn About the Structure of Language|Source - What Does BERT Learn About the Structure of Language]]

## Open Questions
- When does geometric recovery imply a meaningful computational representation rather than a convenient readout?
- Can similar geometric analyses be applied to activation spaces in contemporary LLMs?
