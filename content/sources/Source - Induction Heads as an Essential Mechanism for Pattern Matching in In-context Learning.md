---
title: Source - Induction Heads as an Essential Mechanism for Pattern Matching in In-context Learning
type: source
status: active
updated: 2026-04-23
tags:
  - source
  - mechanistic-interpretability
  - induction-heads
  - in-context-learning
  - large-language-models
---

## Summary
Crosbie and Shutova study induction heads in few-shot in-context learning settings for Llama-3-8B and InternLM2-20B. Unlike Olsson et al.'s foundational source, which gives strongest causal evidence in small attention-only models and more indirect evidence for larger models, this follow-up directly evaluates induction-head interventions in large open models on abstract pattern-recognition and NLP tasks.

## Key Points
- Source fact: the paper evaluates Llama-3-8B and InternLM2-20B.
- Source fact: the authors identify candidate induction heads by computing prefix-matching scores on repeated random token sequences.
- Source fact: they mean-ablate or zero-ablate the top 1% and 3% of heads by prefix-matching score, with random-head ablations as controls.
- Source fact: on abstract pattern-recognition tasks, ablating high-prefix-matching heads causes much larger performance drops than ablating comparable random heads.
- Source fact: on NLP tasks, induction-head ablations reduce the benefit from few-shot examples, especially in semantically unrelated label settings designed to force reliance on in-context learning.
- Source fact: attention knockout experiments block tokens from attending to tokens that previously followed similar tokens, directly targeting the induction attention pattern.
- Source fact: the authors argue that the attention-knockout results support the specific role of prefix matching and copying, not merely the generic importance of the ablated heads.

## Details
The paper explicitly builds on the induction-head account from [[Source - In-context Learning and Induction Heads|Olsson et al.]]. It shifts the evidence target from training-dynamics and small-model circuit analysis toward task-level few-shot ICL performance in larger modern transformer models.

The experimental setup has three important pieces:
- prefix-matching scores identify candidate induction heads
- head ablations test whether those heads are important for task performance
- attention knockout tests whether the induction-style attention pattern itself matters

The paper's abstract-pattern tasks are designed to reduce reliance on memorized world knowledge or task semantics. The NLP experiments include semantically unrelated labels to make the model rely more heavily on the examples in context.

## Synthesis / Interpretation
This source materially extends the current induction-head cluster. It does not replace Olsson et al. as the canonical conceptual source, but it strengthens the case that induction heads matter for task-level few-shot ICL in large models.

The source should be treated as follow-up evidence rather than a new concept cluster. Its main wiki role is to update the evidence balance around whether induction heads are causally important in larger models.

Within `induction_heads_icl`, this page is the large-model intervention and attention-knockout follow-up. It should stay distinct from `neural_nlp_probing` because the key evidence comes from targeted interventions, not probe readout performance.

## Related Pages
- [[../concepts/Induction Heads|Induction Heads]]
- [[../concepts/In-Context Learning|In-Context Learning]]
- [[../overviews/Induction Heads and In-Context Learning Overview|Induction Heads and In-Context Learning Overview]]
- [[../analyses/Evidence That Induction Heads Support In-Context Learning|Evidence That Induction Heads Support In-Context Learning]]
- [[Source - In-context Learning and Induction Heads]]

## Source Identification
- Authors: James Crosbie and Ekaterina Shutova
- Title: *Induction Heads as an Essential Mechanism for Pattern Matching in In-context Learning*

## Open Questions
- How robust are the reported effects across more model families, prompt formats, and task types?
- Do high prefix-matching scores always identify mechanistic induction heads, or only behavioral induction-head candidates?
- How should this evidence be combined with causal tracing or circuit-level analysis in large models?
