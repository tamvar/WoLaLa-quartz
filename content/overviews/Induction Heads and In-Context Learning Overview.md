---
title: Induction Heads and In-Context Learning Overview
type: overview
status: active
updated: 2026-04-23
tags:
  - overview
  - induction-heads
  - in-context-learning
  - mechanistic-interpretability
---

## Summary
This overview tracks a topic centered on induction heads and in-context learning. It is distinct from the neural NLP probing literature because it focuses on transformer circuits and causal or mechanistic evidence, not diagnostic readout of linguistic properties.

## Key Points
- Source fact: Olsson et al. define induction heads as attention heads that perform repeated-sequence completion.
- Source fact: the paper connects induction-head formation to an early-training phase change where in-context learning sharply improves.
- Source fact: the strongest evidence is in small attention-only models; evidence for large models with MLPs is more indirect and correlational.
- Source fact: Crosbie and Shutova evaluate induction heads in Llama-3-8B and InternLM2-20B using prefix-matching scores, head ablations, and attention knockout.
- Source fact: Crosbie and Shutova report that ablating high-prefix-matching heads damages few-shot ICL performance more than comparable random-head ablations, especially on abstract pattern-recognition tasks and semantically unrelated label settings.
- Synthesis: prefix-matching scores should be treated as candidate-head evidence unless supported by stronger causal tests such as ablations or attention knockout.
- Synthesis: the cluster should track mechanisms, circuits, ablations, attention-pattern interventions, and training dynamics rather than treating induction heads as another probe result.

## Topic Map
- Core concepts: [[../concepts/Induction Heads|Induction Heads]], [[../concepts/In-Context Learning|In-Context Learning]]
- Canonical source: [[../sources/Source - In-context Learning and Induction Heads|Source - In-context Learning and Induction Heads]]
- Follow-up source: [[../sources/Source - Induction Heads as an Essential Mechanism for Pattern Matching in In-context Learning|Source - Induction Heads as an Essential Mechanism for Pattern Matching in In-context Learning]]
- Initial analysis: [[../analyses/Evidence That Induction Heads Support In-Context Learning|Evidence That Induction Heads Support In-Context Learning]]

## Details
[[../sources/Source - In-context Learning and Induction Heads|Olsson et al.]] are the cluster's canonical starting point because they connect a specific circuit story, training-phase changes, and direct small-model ablations. The page's core question is not whether some property is readable from activations, but whether a concrete attention-head mechanism helps implement context-sensitive behavior.

[[../sources/Source - Induction Heads as an Essential Mechanism for Pattern Matching in In-context Learning|Crosbie and Shutova]] extend that question into larger open models by combining prefix-matching-based head selection with ablations and attention knockout. This follow-up strengthens the cluster's intervention-focused evidence without replacing the conceptual role of [[../sources/Source - In-context Learning and Induction Heads|Olsson et al.]].

## Boundary
This cluster should stay separate from [[Neural NLP Probing Overview]].

The probing cluster asks: what information is extractable from representations?

This cluster asks: what transformer circuits implement context-sensitive behavior?

Cross-links are useful only where a page directly compares evidence standards, causal claims, or methods. Avoid folding induction heads into the probing taxonomy unless a future source explicitly uses probing-style methodology.

## Related Pages
- [[Neural NLP Probing Overview]]
- [[../concepts/Induction Heads|Induction Heads]]
- [[../analyses/Evidence That Induction Heads Support In-Context Learning|Evidence That Induction Heads Support In-Context Learning]]

## Sources
- [[../sources/Source - In-context Learning and Induction Heads|Source - In-context Learning and Induction Heads]]
- [[../sources/Source - Induction Heads as an Essential Mechanism for Pattern Matching in In-context Learning|Source - Induction Heads as an Essential Mechanism for Pattern Matching in In-context Learning]]

## Open Questions
- How much do prefix-matching scores identify true mechanistic induction heads versus behaviorally similar heads?
- Which later sources best validate, extend, or challenge the induction-head account?
