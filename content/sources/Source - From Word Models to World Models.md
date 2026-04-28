---
title: Source - From Word Models to World Models
type: source
status: active
updated: 2026-04-25
tags:
  - source
  - world-models
  - language-of-thought
  - cognition
---

## Summary
Lionel Wong, Gabriel Grand, and colleagues propose "rational meaning construction", a framework that combines large language models with probabilistic programs. Rather than treating word prediction alone as a theory of understanding, the paper maps natural language into a probabilistic language of thought and uses inference over structured world models to support downstream reasoning.

## Key Points
- Source fact: the paper frames linguistic meaning as a context-sensitive mapping from natural language into a probabilistic language of thought.
- Source fact: its architecture combines large language models for broad-coverage translation with probabilistic programs for inference and world modeling.
- Source fact: the paper presents examples across probabilistic, logical, relational, visual, physical, and social reasoning.
- Source fact: it treats language and thought as deeply related but distinct, and positions the system as an interface between linguistic input and structured cognition.
- Source fact: the paper argues that language can help construct and update world models, not just label already-fixed symbolic states.

## Details
The paper is explicitly framed against a simple scaling-only picture. It situates current LLMs within a broader cognitive architecture in which language interacts with structured representations for world modeling, probabilistic inference, and planning. Its key proposal is "rational meaning construction": LLMs generate code-like translations into a probabilistic programming substrate, and Bayesian inference over that substrate yields coherent reasoning.

The paper therefore treats meaning as something richer than next-token prediction but does not return to a purely classical symbolic pipeline. Instead, it combines neural broad coverage with structured reasoning modules, including probabilistic programs and domain-specific symbolic components such as simulators or planners.

## Synthesis / Interpretation
Within WoLaLa, this source is the most constructive programmatic counterpart to the critical sources in the batch. [[Source - Climbing Towards NLU|Bender and Koller]] argue that form-only training is insufficient for meaning; this paper sketches one way of going beyond form-only language modeling without discarding modern LLMs altogether.

It therefore belongs at the interface of language meaning, cognitive architecture, and reverse-engineering or mind-design style modeling.

## Related Pages
- [[../concepts/Meaning and Reference in Language Models|Meaning and Reference in Language Models]]
- [[../analyses/What Would Count as Meaning or Reference in a Language Model|What Would Count as Meaning or Reference in a Language Model]]
- [[../overviews/Meaning, Reference, and Distributional Language Overview|Meaning, Reference, and Distributional Language Overview]]

## Source Identification
- Authors: Lionel Wong, Gabriel Grand, and colleagues
- Title: *From Word Models to World Models*

## Open Questions
- How much of this framework is a proposal for future systems rather than a claim about what current LLMs already do?
- Does mapping language into a probabilistic language of thought solve the meaning problem, or relocate it into a richer architecture?
