---
title: Source - Dissociating Language and Thought in Large Language Models
type: source
status: active
updated: 2026-05-03
tags:
  - source
  - language
  - cognition
  - understanding
  - neuroscience
---

## Summary
Kyle Mahowald, Anna A. Ivanova, Idan A. Blank, Nancy Kanwisher, Joshua B. Tenenbaum, and Evelina Fedorenko argue that current debates about LLMs often conflate language with thought. Their central distinction is between formal linguistic competence, or getting the form of language right, and functional linguistic competence, or using language to reason, track situations, and pursue goals in the world. They argue that contemporary LLMs are much stronger on the former than the latter, and that future human-like systems may need a more modular architecture that separates language processing from broader cognitive capacities.

## Key Points
- the paper argues against both the `good at language -> good at thought` fallacy and the `bad at thought -> bad at language` fallacy.
- it distinguishes formal linguistic competence from functional linguistic competence and grounds that distinction in human neuroscience.
- it argues that current LLMs perform surprisingly well on many tasks involving formal linguistic competence, including structure-sensitive and abstraction-heavy aspects of language.
- it argues that LLM performance on functional linguistic competence remains uneven and often depends on fine-tuning or the addition of external modules.
- it suggests that more human-like language use may require separate or partially separate mechanisms for language form, world knowledge, reasoning, and social inference.
- it treats modularity, whether architectural or emergent, as a promising route beyond simple scale-only expectations.

## Details
The paper is framed as a correction to a recurring mistake in LLM discourse. Fluent language output tempts people to infer rich thought, reasoning, and world understanding. Conversely, visible failures on planning, commonsense, or theory-of-mind tasks tempt people to conclude that the models are poor models of language itself. Mahowald and colleagues argue that both inferences are too quick.

Their proposed remedy is a distinction between formal and functional linguistic competence. Formal competence concerns the ability to produce and interpret well-formed linguistic structure, including hierarchical and abstract regularities. Functional competence concerns using language in real-world contexts, where language must interact with world knowledge, situation modeling, pragmatics, reasoning, and social cognition.

The neuroscience background is central to the paper’s framing. The authors argue that in humans, language-selective brain regions support formal linguistic processing, while broader reasoning, theory-of-mind, and other domain-general or partially distinct systems support many tasks involved in functional language use. That dissociation matters because it suggests that failure on non-linguistic tasks should not automatically be taken as evidence that a system lacks all linguistically relevant competence.

At the same time, the paper is not a defense of broad understanding claims for present-day LLMs. It repeatedly emphasizes that functional competence remains patchy. Performance on pragmatics, discourse tracking, formal reasoning, world knowledge, and theory-of-mind-style tasks is inconsistent and often improves mainly when models are fine-tuned or augmented with additional machinery. The authors therefore argue that next-word prediction alone appears much better at producing formal competence than at producing robust functional competence.

The constructive end of the paper is a modularity proposal. Rather than expecting one scale-only language model to cover all aspects of language and thought, the paper points toward systems that combine language processing with separate memory, reasoning, planning, or multimodal modules. It also treats [[Source - From Word Models to World Models|Wong et al.]] as an example of this more structured direction.

## Interpretation
This source is an important bridge between debates over meaning and reference and broader language-cognition questions. It strengthens the caution already visible in [[Source - Climbing Towards NLU|Bender and Koller]], but in a more differentiated way: text-only systems may still be strong models of formal linguistic competence even when they fall short on richer forms of understanding.

It also sharpens the vocabulary available for later evaluation. Instead of asking only whether a model does or does not understand language, the paper encourages separate questions about formal competence, functional competence, reasoning, pragmatics, and the architecture that coordinates them.

## Related Pages
- [[../concepts/Meaning and Reference in Language Models|Meaning and Reference in Language Models]]
- [[../analyses/What Would Count as Meaning or Reference in a Language Model|What Would Count as Meaning or Reference in a Language Model]]
- [[../overviews/Meaning, Reference, and Distributional Language Overview|Meaning, Reference, and Distributional Language Overview]]

## Source Identification
- Authors: Kyle Mahowald, Anna A. Ivanova, Idan A. Blank, Nancy Kanwisher, Joshua B. Tenenbaum, and Evelina Fedorenko
- Title: *Dissociating language and thought in large language models*

## Open Questions
- How much functional competence can genuinely be learned from linguistic input alone?
- Which current LLM benchmarks cleanly measure formal competence, and which ones covertly depend on broader reasoning or social inference?
- Would modular architectures produce a better model of human-like language use than scale alone?
