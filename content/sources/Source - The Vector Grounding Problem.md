---
title: Source - The Vector Grounding Problem
type: source
status: active
updated: 2026-04-26
tags:
  - source
  - grounding
  - meaning
  - reference
  - philosophy-of-language
---

## Summary
Dimitri Coelho Mollo and Raphaël Millière revisit the classical symbol grounding problem for vector-based language models. They argue that many grounding debates conflate distinct notions, and that the crucial issue for LLMs is referential grounding: whether internal states and outputs can stand in world-involving relations that make them meaningful independently of external interpretation.

## Key Points
- the paper reformulates the symbol grounding problem as the `Vector Grounding Problem` for vector-based models such as LLMs.
- it distinguishes multiple notions of grounding and argues that only `referential grounding` is central to the key philosophical issue.
- the authors argue that multimodality and embodiment are neither necessary nor sufficient for solving the grounding problem.
- they provide two routes by which LLMs may achieve referential grounding:
  - preference fine-tuning that introduces world-involving success conditions
  - pre-training alone in limited domains, where optimization can select internal states that track worldly features
- the paper explicitly separates grounding from stronger claims about understanding, agency, or knowledge.

## Details
The paper begins from the familiar challenge: LLMs learn from text but generate text that often appears meaningful and topic-sensitive. Rather than treating this as simply the old symbol grounding problem, the authors argue that vector-based systems raise an analogous but not identical issue.

Their main conceptual contribution is to sort out the senses of `grounding` that are often run together. On their account, much of the debate is misdirected because grounding is asked to do too much explanatory work at once. The relevant question is narrower: whether the model's internal states and outputs can come to have world-involving content that is not merely projected onto them by human interpreters.

Their positive answer is qualified but substantial. Referential grounding can arise through fine-tuning regimes that impose extra-linguistic norms such as factuality, and in some cases through pre-training alone when the optimization process rewards internal states that track stable worldly structure. The paper therefore rejects a simple equation between grounding and embodiment.

## Interpretation
This paper is a bridge source. It sits between skeptical claims that text-only systems cannot mean anything, and stronger positive claims that LLMs already understand. It narrows the issue to grounding and argues that the problem is solvable in principle and in some cases already partly solved in practice.

This makes it especially useful alongside [[Source - Climbing Towards NLU|Bender and Koller]], [[Source - Do Language Models Refer|Mandelkern and Linzen]], and [[Source - Meaning Without Reference in Large Language Models|Piantadosi and Hill]]. It provides a more fine-grained vocabulary for asking which semantic deficits are about reference, which are about grounding, and which are really about stronger cognitive capacities.

## Related Pages
- [[../concepts/Meaning and Reference in Language Models|Meaning and Reference in Language Models]]
- [[../analyses/What Would Count as Meaning or Reference in a Language Model|What Would Count as Meaning or Reference in a Language Model]]
- [[../overviews/Meaning, Reference, and Distributional Language Overview|Meaning, Reference, and Distributional Language Overview]]

## Source Identification
- Authors: Dimitri Coelho Mollo and Raphaël Millière
- Title: *The Vector Grounding Problem*

## Open Questions
- How much of the paper's positive case depends on specific fine-tuning setups rather than on generic language-model pre-training?
- If referential grounding is achieved, what still blocks the move to stronger claims about understanding or agency?
