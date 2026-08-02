---
title: Source - Learning to Summarize from Human Feedback
type: source
status: active
updated: 2026-07-29
ingestion_depth: brief
tags:
  - source
  - brief
  - summarization
  - rlhf
  - evaluation
  - human-feedback
---

## Summary
Nisan Stiennon, Long Ouyang, Jeff Wu, Daniel Ziegler, Ryan Lowe, Chelsea Voss, Alec Radford, Dario Amodei, and Paul Christiano argue that standard supervised summarization objectives and metrics such as ROUGE are poor proxies for the quality people actually care about. They collect human preference comparisons, train a reward model on those comparisons, and then optimize summarization behavior against that reward model. For WoLaLa, the paper matters because it is one of the clearest early cases where training and evaluation are explicitly reorganized around human preference rather than text matching alone.

## Strand Connections

- Primary: [[../overviews/Applications and Best Practices Overview|Applications and Best Practices]] (strand 6)
- Secondary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)

## Key Points
- The paper argues that reference summaries and ROUGE are rough and often misleading proxies for summary quality.
- Human comparison data is used both to train a reward model and to define the target for reinforcement learning.
- The resulting models outperform supervised baselines by human judgment, even when those baselines optimize conventional metrics.
- The source is an early methodological hinge from benchmark optimization toward preference-based post-training.

## WoLaLa Relevance
For WoLaLa, this source matters because it makes objective mismatch explicit. A language model can optimize the wrong textual proxy while missing what human users want from an output. That lesson generalizes beyond summarization: later LLM use increasingly depends on judged helpfulness, reliability, and interaction quality rather than only on gold-label overlap. The paper therefore belongs in strand 6 as a methodological precursor to later RLHF and evaluation redesign.

Its secondary strand-1 relevance is cautionary. If preferred outputs can be produced by changing the reward target, then downstream behavioral quality does not straightforwardly reveal what the model "knows" in a pure pretraining sense. Competence, objective, and display behavior should be kept distinct.

## Limitation Or Open Question
The study is task-specific and does not by itself solve the broader problem of alignment or evaluation across open-ended language use. It leaves open which human preferences are stable, which are brittle, and how reward optimization changes the internal tradeoffs of the model.

## Related Pages
- [[../overviews/Applications and Best Practices Overview|Applications and Best Practices Overview]]
- [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations Overview]]
- [[../sources/Source - InstructGPT|Source - InstructGPT]]
- [[../sources/Source - Evaluating Factual Consistency of Summaries with Large Language Models|Source - Evaluating Factual Consistency of Summaries with Large Language Models]]

## Source Identification
- Authors: Nisan Stiennon, Long Ouyang, Jeff Wu, Daniel M. Ziegler, Ryan Lowe, Chelsea Voss, Alec Radford, Dario Amodei, Paul Christiano, and colleagues
- Title: *Learning to Summarize from Human Feedback*
- Year: 2020
- Source type: conference paper / arXiv preprint
- Publication context: NeurIPS 2020 workshop-era OpenAI research paper

## Source Access
- Public source: [arXiv abstract page](https://arxiv.org/abs/2009.01325)
