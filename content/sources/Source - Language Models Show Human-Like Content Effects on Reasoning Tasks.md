---
title: Source - Language Models Show Human-Like Content Effects on Reasoning Tasks
type: source
status: active
updated: 2026-07-27
ingestion_depth: deep
tags:
  - source
  - deep
  - cognition
  - reasoning
  - language-models
  - ssh
---

## Summary
Lampinen, Dasgupta, Chan, Sheahan, Creswell, Kumaran, McClelland, and Hill test whether language models show the same kind of content effects that shape human reasoning. Across natural-language inference, syllogistic validity judgments, and Wason-style selection problems, they find that models, like humans, perform better when semantic content supports the intended inference and worse when content conflicts with formal validity. For WoLaLa, the paper matters because it cuts both ways: it shows a real cognitive parallel between model behavior and human reasoning, but it also shows that this parallel is not the same as content-independent logical competence.

## Strand Connections

- Primary: [[../overviews/Cultural, Cognitive, and SSH Perspectives Overview|Cultural, Cognitive, and SSH Perspectives]] (strand 5)
- Secondary: [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering]] (strand 7)

## Key Points
- The paper asks whether language models reproduce human content effects rather than only whether they solve reasoning tasks above chance.
- The main result is that model success varies with semantic plausibility in ways that resemble human reasoning biases.
- The comparison matters because it links model behavior to a specific cognitive phenomenon rather than to a generic benchmark score.
- The source does not show that language models possess human-like reasoning in a strong sense.
- It is especially useful for separating pattern-level similarity from stronger claims about explanation or mechanism.

## Details
The paper begins from a familiar criticism of current language models: they often appear brittle on abstract reasoning tasks. But instead of treating human reasoning as the ideal of perfectly content-free logic, the authors emphasize that human reasoning is itself systematically shaped by semantic content. People do better when a problem's content aligns with background expectations and worse when it conflicts with them, even when the formal structure is the same.

Their central question is whether language models show an analogous pattern. To test this, the paper compares humans and several large language models across three families of tasks: natural-language inference, syllogistic reasoning, and the Wason selection task. In each case, the design contrasts problems whose semantic content supports the relevant inference with matched problems whose content does not.

The reported result is not simply that models sometimes fail. It is that their successes and failures track content in a recognizably human-like way. Models are more accurate when the content of a task supports the logically correct answer, and they are less reliable when semantic expectations pull in another direction. The paper also reports lower-level parallels, including relations between model answer distributions and human response times.

For WoLaLa, this matters because it sharpens a recurring ambiguity in model-cognition comparisons. A result like this is stronger than a bare benchmark claim, because it identifies a shared behavioral pattern. But it is weaker than a claim that the model and the human mind implement the same reasoning mechanism. The paper therefore supports a moderate position: language models can illuminate some features of human cognition without thereby becoming full theories of human reasoning.

## Interpretation
This source is a strong cognition bridge because it shows that model behavior can mirror structured features of human reasoning performance, not only task accuracy. At the same time, the result is compatible with multiple explanations. It may reflect shared sensitivity to semantic priors, but it does not settle whether the underlying representational or inferential organization is the same.

The paper is especially useful alongside [[../sources/Source - Dissociating Language and Thought in Large Language Models|Dissociating Language and Thought in Large Language Models]] and [[../sources/Source - Building Machines That Learn and Think Like People|Building Machines That Learn and Think Like People]]. It adds evidence that model behavior sometimes aligns with human cognition in nontrivial ways, while still leaving open whether that alignment amounts to human-like thought.

## Related Pages
- [[../overviews/Cultural, Cognitive, and SSH Perspectives Overview|Cultural, Cognitive, and SSH Perspectives Overview]]
- [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering Overview]]
- [[../sources/Source - Dissociating Language and Thought in Large Language Models|Source - Dissociating Language and Thought in Large Language Models]]
- [[../sources/Source - Building Machines That Learn and Think Like People|Source - Building Machines That Learn and Think Like People]]
- [[../sources/Source - The Child as Hacker|Source - The Child as Hacker]]

## Source Identification
- Authors: Andrew K. Lampinen, Ishita Dasgupta, Stephanie C. Y. Chan, Hannah R. Sheahan, Antonia Creswell, Dharshan Kumaran, James L. McClelland, and Felix Hill
- Title: "Language models show human-like content effects on reasoning tasks"
- Year: 2024 local version; first public preprint 2022
- Source type: preprint
- Publication context: arXiv `2207.07051`

## Source Access
- Public source: [arXiv abstract page](https://arxiv.org/abs/2207.07051)

## Open Questions
- Which parts of the reported human-model similarity depend on semantic priors, and which depend on more general task heuristics?
- What additional evidence would be needed to move from behavioral resemblance to stronger explanatory comparison?
