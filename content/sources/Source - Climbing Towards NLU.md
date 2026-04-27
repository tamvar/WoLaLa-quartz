---
title: Source - Climbing Towards NLU
type: source
status: active
updated: 2026-04-25
tags:
  - source
  - meaning
  - reference
  - philosophy-of-language
---

# Source - Climbing Towards NLU

## Summary
Emily M. Bender and Alexander Koller argue that success on form-only language modeling tasks does not by itself justify claims about linguistic meaning or understanding. The paper is a central critical anchor because it sharply distinguishes form, conventional meaning, and communicative intent.

## Key Points
- Source fact: the paper argues that a system trained only on linguistic form has, in principle, no route to learning meaning.
- Source fact: it defines linguistic meaning as a relation between linguistic form and communicative intent, rather than as string prediction success.
- Source fact: it reviews hype around large language models and warns that terms such as "understand", "comprehend", and "meaning" are often used imprecisely in both research and public discourse.
- Source fact: it distinguishes form, conventional meaning, and communicative intent, and argues that communicative intent is grounded outside language.
- Source fact: it treats human-analogous NLU as a broader challenge involving language structure, use, and grounding in the world.

## Details
The paper's opening claim is methodological as much as philosophical: if training data contains only form, then the resulting model cannot in principle learn the relation between form and communicative intent. Bender and Koller therefore argue that strong meaning or understanding claims about form-only LMs are overclaims.

Their framework distinguishes:
- form: observable strings, symbols, sounds, or glyphs
- conventional meaning: the standing meaning associated with an expression in a linguistic system
- communicative intent: what a speaker is trying to convey in context

This distinction lets the paper criticize a range of "BERTology" and press-language claims without denying that large language models capture important aspects of linguistic form. The authors explicitly allow that such models may become important components of broader NLU systems, while denying that next-token or form-only learning is already enough for meaning.

## Synthesis / Interpretation
Within this literature, this source is the main cautionary anchor. It constrains how meaning and understanding should be discussed: benchmark success, fluent output, or structural regularity should not automatically be upgraded into meaning claims.

It also sets up a productive tension with [[Source - Do Language Models Refer|Mandelkern and Linzen]], who argue that a specific semantic relation, reference, may still be available to language-model outputs under an externalist account.

## Related Pages
- [[../concepts/Meaning and Reference in Language Models|Meaning and Reference in Language Models]]
- [[../analyses/What Would Count as Meaning or Reference in a Language Model|What Would Count as Meaning or Reference in a Language Model]]
- [[../overviews/Meaning, Reference, and Distributional Language Overview|Meaning, Reference, and Distributional Language Overview]]

## Source Identification
- Authors: Emily M. Bender and Alexander Koller
- Title: *Climbing towards NLU: On Meaning, Form, and Understanding in the Age of Data*

## Open Questions
- How far can a form-only critique be extended once models are augmented with tools, memory, or world-interaction modules?
- Which current evaluation results actually bear on communicative intent, rather than only on form-sensitive competence?
