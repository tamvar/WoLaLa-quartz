---
title: Source - In-context Learning and Induction Heads
type: source
status: active
updated: 2026-04-23
tags:
  - source
  - mechanistic-interpretability
  - induction-heads
  - in-context-learning
---

## Summary
Olsson et al. argue that induction heads may be a major mechanism behind in-context learning in transformer language models. The source is framed as mechanistic interpretability: it studies attention-head circuits, training dynamics, ablations, and phase changes rather than asking what linguistic labels are extractable from representations.

## Key Points
- Source fact: the paper defines induction heads as attention heads that implement sequence-completion behavior of the form `[A][B] ... [A] -> [B]`.
- Source fact: in small attention-only models, the authors present stronger causal/mechanistic evidence that induction heads contribute to in-context learning.
- Source fact: in larger models with MLPs, the authors present mainly indirect and correlational evidence, and explicitly note possible confounds.
- Source fact: the paper measures in-context learning mainly as decreasing loss at later token positions in the context, not as task-specific few-shot benchmark performance.
- Source fact: the authors report an early training transition in which induction heads emerge.
- Source fact: they also report a sharp improvement in their measure of in-context learning during the same period.
- Source fact: the evidence package includes co-occurrence, architectural co-perturbation, test-time attention-head ablations in small models, examples of broader induction-head behavior, mechanistic plausibility, and continuity from small to larger models.
- Source fact: `Induction heads.pdf` was checked separately as a likely alternate-copy or variant candidate, but this source page treats `Olsson et al. (2022) In-context Learning and Induction Heads.pdf` as canonical.

## Details
The source connects three levels of analysis:
- circuit mechanism: previous-token heads and induction heads cooperate to support repeated-sequence completion
- training dynamics: induction heads appear during an "induction bump" or phase change early in training
- behavioral metric: loss decreases more for later context positions as the model learns to use context

The authors explicitly separate evidence strength by model class. The case is strongest for small attention-only models, where ablations and mechanistic analysis are more tractable. For larger transformer models with MLPs, the paper argues by converging indirect evidence rather than a full reverse-engineered proof.

## Synthesis / Interpretation
This source opens a distinct line of inquiry. Neural NLP probing asks what information is readable from representations; this source asks how a transformer circuit may implement a behavioral capability. The appropriate synthesis target is therefore mechanistic accounts of in-context learning, not another page about diagnostic classifiers.

This page remains the canonical conceptual anchor because it ties together the circuit hypothesis, the induction-bump training story, and the strongest direct small-model causal evidence in this source set.

## Related Pages
- [[../concepts/Induction Heads|Induction Heads]]
- [[../concepts/In-Context Learning|In-Context Learning]]
- [[../overviews/Induction Heads and In-Context Learning Overview|Induction Heads and In-Context Learning Overview]]
- [[../analyses/Evidence That Induction Heads Support In-Context Learning|Evidence That Induction Heads Support In-Context Learning]]

## Source Identification
- Authors: Catherine Olsson and colleagues
- Title: *In-context Learning and Induction Heads*

## Open Questions
- How much of the induction-head account explains in-context learning in large transformer models with MLPs?
- Which later mechanistic-interpretability sources strengthen, revise, or dispute this account?
