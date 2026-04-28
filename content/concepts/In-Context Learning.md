---
title: In-Context Learning
type: concept
status: active
updated: 2026-04-23
tags:
  - concept
  - in-context-learning
  - transformers
---

## Summary
In-context learning is a model's ability to use information in the prompt or context at inference time, without changing its weights. In Olsson et al., the operational focus is loss improvement at later token positions, not only few-shot task performance.

## Key Points
- Source fact: Olsson et al. distinguish task-level few-shot learning from a broader loss-based view of in-context learning.
- Source fact: their main metric compares later-context token loss against earlier-context token loss.
- Source fact: the paper argues that induction heads may explain much of this general loss-based in-context learning.
- Source fact: the authors connect in-context learning to safety because model behavior can depend strongly on long context at test time.

## Details
[[../sources/Source - In-context Learning and Induction Heads|Olsson et al.]] use a broad macro-level measure: tokens later in a context become easier to predict as the model learns to use earlier context. This differs from evaluating a model on a hand-selected few-shot task such as translation or arithmetic.

This definition is useful for mechanistic study because it allows training dynamics and attention-head formation to be compared across model snapshots and architectures.

[[../sources/Source - Induction Heads as an Essential Mechanism for Pattern Matching in In-context Learning|Crosbie and Shutova]] emphasize a narrower task-level few-shot view in larger models. Keeping both notions visible helps the wiki avoid collapsing "in-context learning" into only benchmark prompting behavior or only loss-based phase-change evidence.

This page belongs with the induction-head cluster rather than the probing cluster because its central question is how context-sensitive behavior is implemented, not which labels can be read out from a representation.

## Related Pages
- [[Induction Heads]]
- [[../overviews/Induction Heads and In-Context Learning Overview|Induction Heads and In-Context Learning Overview]]
- [[../analyses/Evidence That Induction Heads Support In-Context Learning|Evidence That Induction Heads Support In-Context Learning]]

## Sources
- [[../sources/Source - In-context Learning and Induction Heads|Source - In-context Learning and Induction Heads]]

## Open Questions
- How should task-level few-shot learning and loss-based in-context learning be related in future wiki pages?
- Which mechanisms besides induction heads contribute to in-context learning?
