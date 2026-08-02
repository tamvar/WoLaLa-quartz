---
title: Source - Scaling Language Models from Gopher
type: source
status: active
updated: 2026-07-29
ingestion_depth: brief
tags:
  - source
  - brief
  - scaling
  - gopher
  - evaluation
  - foundation-models
---

## Summary
Jack W. Rae and a large DeepMind team present Gopher, a 280B-parameter Transformer language model, together with an unusually broad evaluation and analysis program. The paper matters for WoLaLa because it does not treat scaling as a single upward line. Instead, it asks where scale helps, where it helps less, and how performance intersects with training data, bias, toxicity, and safety. That makes it one of the clearest scaling-era sources for separating headline language-model gains from the uneven profile of the resulting capabilities.

## Strand Connections

- Primary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)
- Secondary: [[../overviews/Applications and Best Practices Overview|Applications and Best Practices]] (strand 6)

## Key Points
- The paper evaluates Transformer language models across a wide scale range up to Gopher at 280B parameters.
- Scale yields strong gains on many reading-comprehension, fact-checking, and language-understanding tasks, but much weaker gains on some logical and mathematical reasoning tasks.
- The source also analyzes training data composition, toxicity, bias, and safety-relevant downstream concerns.
- Its importance lies in disaggregation: scaling improves many things, but not all things equally.

## WoLaLa Relevance
For strand 1, the paper is useful because it sharpens a familiar WoLaLa question: what does improved next-token training at large scale actually buy? The answer here is not simply "more intelligence." Some competence families improve markedly, while others remain stubbornly limited. That makes the paper a valuable counterweight both to scale skepticism that ignores real gains and to triumphalist narratives that treat all benchmark growth as one undifferentiated phenomenon.

For strand 6, the source matters because it models a relatively serious evaluation posture. It does not stop at aggregate scores. It asks how model size, data mixture, harms, and task profile interact. That broader frame is methodologically important for WoLaLa because language-model assessment should not reduce to a single leaderboard or a single extrapolated story about emergence.

## Limitation Or Open Question
The paper is still anchored in a large benchmark suite rather than in a linguistic or cognitive theory of competence. It therefore clarifies the profile of scaling gains without settling what those gains mean explanatorily.

## Related Pages
- [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations Overview]]
- [[../overviews/Applications and Best Practices Overview|Applications and Best Practices Overview]]
- [[../sources/Source - Language Models are Few-Shot Learners|Source - Language Models are Few-Shot Learners]]
- [[../sources/Source - T5|Source - T5]]
- [[../sources/Source - When Do You Need Billions of Words of Pretraining Data|Source - When Do You Need Billions of Words of Pretraining Data]]

## Source Identification
- Authors: Jack W. Rae, Sebastian Borgeaud, Trevor Cai, Katie Millican, Jordan Hoffmann, and colleagues
- Title: *Scaling Language Models: Methods, Analysis & Insights from Training Gopher*
- Year: 2021
- Source type: technical report / arXiv preprint
- Publication context: DeepMind research report

## Source Access
- Public source: [arXiv abstract page](https://arxiv.org/abs/2112.11446)
