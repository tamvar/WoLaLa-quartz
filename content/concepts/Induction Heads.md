---
title: Induction Heads
type: concept
status: active
updated: 2026-04-23
tags:
  - concept
  - mechanistic-interpretability
  - induction-heads
  - transformers
---

# Induction Heads

## Summary
Induction heads are transformer attention heads that help continue repeated token patterns. In Olsson et al.'s framing, they search the context for an earlier occurrence of the current token and promote the token that followed it, implementing behavior like `[A][B] ... [A] -> [B]`.

## Key Points
- Source fact: Olsson et al. define induction heads behaviorally by prefix matching and copying on repeated random token sequences.
- Source fact: the proposed mechanism involves at least two heads in small attention-only models: a previous-token head and a later induction head.
- Source fact: induction heads are algorithmic rather than memorized n-gram tables; the rule applies across arbitrary token identities.
- Source fact: the authors argue that in larger models induction heads may support fuzzier or more abstract sequence completion, such as nearest-neighbor-style pattern continuation.

## Details
[[../sources/Source - In-context Learning and Induction Heads|Olsson et al.]] define the basic circuit as:
- a previous-token head copies information from the previous token into the current position
- an induction head uses that information to attend to earlier tokens that were preceded by the current token
- the head output raises the likelihood of the token that followed the earlier matching token

This makes induction heads a mechanistic object: the claim is about a specific computation implemented by attention heads, not merely about whether some property can be decoded from model activations.

[[../sources/Source - Induction Heads as an Essential Mechanism for Pattern Matching in In-context Learning|Crosbie and Shutova]] keep the same object in view while moving to larger models and more task-level interventions. Their work matters here because it tests whether candidate induction heads selected by prefix-matching behavior are causally important for few-shot performance.

## Related Pages
- [[In-Context Learning]]
- [[../overviews/Induction Heads and In-Context Learning Overview|Induction Heads and In-Context Learning Overview]]
- [[../analyses/Evidence That Induction Heads Support In-Context Learning|Evidence That Induction Heads Support In-Context Learning]]

## Sources
- [[../sources/Source - In-context Learning and Induction Heads|Source - In-context Learning and Induction Heads]]

## Open Questions
- Which variants of induction heads exist in larger models with MLPs?
- How should the wiki distinguish literal token-copying induction from more abstract induction-like behavior?
