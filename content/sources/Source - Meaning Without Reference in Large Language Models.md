---
title: Source - Meaning Without Reference in Large Language Models
type: source
status: active
updated: 2026-04-25
tags:
  - source
  - meaning
  - reference
  - conceptual-role
---

# Source - Meaning Without Reference in Large Language Models

## Summary
Steven T. Piantadosi and Felix Hill argue that language models may possess important aspects of meaning even without reference in the strong world-linking sense assumed by many critics. Their central move is to treat meaning as conceptual role: what matters is how internal representational states relate to one another, not whether a model was trained with direct referential grounding.

## Key Points
- Source fact: the paper directly contests the claim that text-only LLMs must lack meaning because they lack reference.
- Source fact: it argues that many meaningful human concepts either lack stable referents or cannot be reduced to reference alone.
- Source fact: the paper uses conceptual role theory to argue that meaning depends on structured relations among internal states.
- Source fact: it argues that the right place to look for meaning in a model is the geometry and dynamics of its internal representations, not only its architecture, training data, or objective.
- Source fact: it treats current LLMs as partial and imperfect, but still plausibly meaning-bearing in ways that resemble human conceptual organization.

## Details
Piantadosi and Hill target the familiar objection, associated especially with [[Source - Climbing Towards NLU|Bender and Koller]], that text-only models cannot have meaning because they lack contact with referents. They argue that this objection assumes too simple a theory of meaning.

Their first move is philosophical: many human concepts are meaningful despite having no clear referent, unstable reference, or only theory-mediated application. They use examples involving abstract terms, imaginary entities, and ordinary concepts whose use depends more on conceptual relations than on a fixed inventory of perceptual features.

Their positive proposal is conceptual role theory. On this view, meaning is constituted by the role a concept plays within a larger network of thought. Applied to LLMs, this means the relevant evidence is relational structure among internal states: how concepts pattern with one another, what inferences and transformations they support, and whether those structures align with human semantic organization.

The paper points to empirical hints in that direction, including representational geometry, cross-lingual alignment, and work suggesting that text-trained models can recover structured conceptual spaces. It does not claim that current LLMs are fully human-like thinkers. Instead, it argues that meaning may already be present in partial form even where direct reference is absent or underdetermined.

## Synthesis / Interpretation
Within WoLaLa, this source is the cleanest current defense of separating meaning from reference. [[Source - Do Language Models Refer|Mandelkern and Linzen]] defend a narrower externalist route to reference; Piantadosi and Hill instead argue that even without settling reference, a model may still instantiate meaningful conceptual organization.

This makes the paper a direct bridge between distributional-semantic traditions and contemporary LLM debates. It is less skeptical than [[Source - Climbing Towards NLU|Bender and Koller]], but it is also not a generic scaling triumphalism paper. Its strongest claim is conceptual: semantic assessment should focus on internal role structure, not only on overt grounding conditions.

## Related Pages
- [[../concepts/Meaning and Reference in Language Models|Meaning and Reference in Language Models]]
- [[../analyses/What Would Count as Meaning or Reference in a Language Model|What Would Count as Meaning or Reference in a Language Model]]
- [[../overviews/Meaning, Reference, and Distributional Language Overview|Meaning, Reference, and Distributional Language Overview]]

## Source Identification
- Authors: Steven T. Piantadosi and Felix Hill
- Title: *Meaning without reference in large language models*

## Open Questions
- How much empirical evidence would be needed to show that LLM internal geometry supports conceptual role rather than only sophisticated correlation?
- Can conceptual-role meaning be combined with externalist reference, or do the two approaches support competing pictures of semantic success?
