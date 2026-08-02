---
title: Source - Language Models are Multilingual Chain-of-Thought Reasoners
type: source
status: active
updated: 2026-07-29
ingestion_depth: brief
tags:
  - source
  - brief
  - multilinguality
  - reasoning
  - chain-of-thought
  - evaluation
---

## Summary
Freda Shi, Mirac Suzgun, Markus Freitag, Xuezhi Wang, Suraj Srivats, Soroush Vosoughi, Hyung Won Chung, Yi Tay, Sebastian Ruder, Denny Zhou, Dipanjan Das, and Jason Wei introduce the Multilingual Grade School Math benchmark and show that large language models can perform chain-of-thought reasoning in ten typologically diverse languages, including underrepresented ones. For WoLaLa, the source matters because it turns multilinguality into a stress test for reasoning claims rather than treating it only as translation or lexical transfer.

## Strand Connections

- Primary: [[../overviews/Applications and Best Practices Overview|Applications and Best Practices]] (strand 6)
- Secondary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)

## WoLaLa Relevance
This source primarily supports [[../overviews/Applications and Best Practices Overview|Applications and Best Practices]] and secondarily [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]]. It is useful because it asks whether chain-of-thought prompting survives beyond English and how strongly performance tracks language frequency in pretraining. The paper therefore helps separate broad reasoning claims from English-centric artifacts and gives multilingual evaluation a more demanding target than simple task transfer.

## Limitation Or Open Question
The benchmark is still narrow, and chain-of-thought prompting may expose learned prompting patterns rather than a language-independent reasoning faculty. The open question is how far multilingual reasoning performance generalizes beyond translated school-math and closely related tasks.

## Related Pages
- [[../overviews/Applications and Best Practices Overview|Applications and Best Practices Overview]]
- [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations Overview]]
- [[../sources/Source - mT5|Source - mT5]]
- [[../sources/Source - On the Multilingual Capabilities of Very Large-Scale English Language Models|Source - On the Multilingual Capabilities of Very Large-Scale English Language Models]]

## Source Identification
- Authors: Freda Shi, Mirac Suzgun, Markus Freitag, Xuezhi Wang, Suraj Srivats, Soroush Vosoughi, Hyung Won Chung, Yi Tay, Sebastian Ruder, Denny Zhou, Dipanjan Das, and Jason Wei
- Title: *Language Models are Multilingual Chain-of-Thought Reasoners*
- Year: 2022
- Source type: research paper
- Publication context: arXiv preprint

## Source Access
- Public source: [arXiv abstract page](https://arxiv.org/abs/2210.03057)
