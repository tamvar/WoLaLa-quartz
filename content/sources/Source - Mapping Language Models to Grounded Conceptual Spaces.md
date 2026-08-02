---
title: Source - Mapping Language Models to Grounded Conceptual Spaces
type: source
status: active
updated: 2026-07-29
ingestion_depth: brief
tags:
  - source
  - brief
  - grounding
  - semantics
  - conceptual-spaces
  - language-models
---

## Summary
Roma Patel and Ellie Pavlick test whether large text-only language models can map words onto grounded conceptual domains once given a small number of world-linked examples. In constrained domains such as directions and colors, larger generative models can learn the taught mapping and generalize to related unseen concepts better than smaller models. For WoLaLa, the paper matters because it offers a bounded constructive middle ground between "text-only models are already grounded" and "text-only models can never support grounding-relevant structure."

## Strand Connections

- Primary: [[../overviews/Meaning, Reference, and Distributional Language Overview|Meaning, Reference, and Distributional Language]] (strand 3)
- Secondary: [[../overviews/Cultural, Cognitive, and SSH Perspectives Overview|Cultural, Cognitive, and SSH Perspectives]] (strand 5)

## WoLaLa Relevance
This source is useful because it sharpens what a positive grounding result would actually look like. The paper does not claim that text pretraining alone gives a model full world-linked meaning. Instead, it asks whether a text-trained model already contains enough conceptual organization that a small amount of grounded supervision can align an entire domain. That makes the result relevant both to semantic optimism and to semantic caution.

It also helps distinguish several semantic claims. The paper supports a limited claim about conceptual structure and data-efficient grounding, not a broad claim about autonomous reference, communicative understanding, or general world modeling. That narrower contribution fits naturally with the existing meaning/reference concept and analysis pages.

## Key Points
- The paper tests whether text-only language models can align words to grounded domains using only a few examples.
- Larger models can generalize from taught concepts such as `left` to related concepts such as `right` in constrained grounded settings.
- The result suggests that pretrained conceptual structure may make later grounding more data-efficient.
- The contribution is about partial alignment in bounded domains, not about full semantic grounding from text alone.

## Limitation Or Open Question
The grounded tasks are intentionally small and structured, so the result does not show that open-ended language understanding, reference, or world modeling can be recovered this way at large scale. The open question is how much of the success depends on genuine conceptual structure and how much on the simplicity of the experimental domains.

## Related Pages
- [[../overviews/Meaning, Reference, and Distributional Language Overview|Meaning, Reference, and Distributional Language Overview]]
- [[../concepts/Meaning and Reference in Language Models|Meaning and Reference in Language Models]]
- [[../analyses/What Would Count as Meaning or Reference in a Language Model|What Would Count as Meaning or Reference in a Language Model]]
- [[../sources/Source - From Word Models to World Models|Source - From Word Models to World Models]]

## Source Identification
- Authors: Roma Patel and Ellie Pavlick
- Title: *Mapping Language Models to Grounded Conceptual Spaces*
- Year: 2022
- Source type: conference paper
- Publication: *International Conference on Learning Representations (ICLR 2022)*

## Source Access
- Public source: [OpenReview page](https://openreview.net/forum?id=gJcEM8sxHK)
