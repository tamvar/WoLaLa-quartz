---
title: Source - Speak, Memory
type: source
status: active
updated: 2026-07-27
ingestion_depth: brief
tags:
  - source
  - brief
  - ssh
  - methodology
  - memorization
  - cultural-analytics
---

## Summary
Chang, Cramer, Soni, and Bamman investigate which books ChatGPT and GPT-4 appear to know by using name-cloze membership-inference prompts. They argue that memorization is uneven, that it tracks web frequency, and that this creates serious validity problems for cultural-analytics work that treats closed models as neutral interpreters of literary corpora. For WoLaLa, the paper is a strong SSH-method source because it ties model opacity, memorization, and downstream research validity together in a concrete literary-research setting.

## Strand Connections

- Primary: [[../overviews/Cultural, Cognitive, and SSH Perspectives Overview|Cultural, Cognitive, and SSH Perspectives]] (strand 5)
- Secondary: [[../overviews/Applications and Best Practices Overview|Applications and Best Practices]] (strand 6)

## WoLaLa Relevance
This paper is useful because it moves beyond generic warnings about training data opacity. It shows a specific way that unknown memorization can distort empirical literary research: models perform better on books they appear to have memorized, which contaminates evaluation and threatens the validity of cultural-analytic conclusions. It also makes a broader methodological point that closed models are difficult to use responsibly when the relevant training exposure is unknown.

## Key Points
- The paper uses membership-style probes to infer which books ChatGPT and GPT-4 likely know.
- It argues that memorization is widespread but highly uneven across books and genres.
- Memorization appears linked to web duplication and discoverability.
- The authors show that model performance on downstream literary tasks is higher for memorized books than for non-memorized books.
- Open models with known training data are presented as methodologically preferable for cultural analytics.

## Limitation Or Open Question
The paper is strongest as a methodological warning, not as a full general theory of memorization. Its probing strategy is clever but indirect, and it is focused on literary-cultural use cases rather than all scholarly applications. The open question is how broadly this validity problem extends across other SSH workflows that use closed language models on partially overlapping corpora.

## Related Pages
- [[../overviews/Cultural, Cognitive, and SSH Perspectives Overview|Cultural, Cognitive, and SSH Perspectives Overview]]
- [[../overviews/Applications and Best Practices Overview|Applications and Best Practices Overview]]
- [[../sources/Source - Human and Machine Language Understanding|Source - Human and Machine Language Understanding]]
- [[../sources/Source - The Generative AI Paradox|Source - The Generative AI Paradox]]
- [[../sources/Source - Are LLMs Like Libraries or Librarians|Source - Are LLMs Like Libraries or Librarians]]

## Source Identification
- Authors: Kent K. Chang, Mackenzie Cramer, Sandeep Soni, and David Bamman
- Title: "Speak, Memory: An Archaeology of Books Known to ChatGPT/GPT-4"
- Year: 2023
- Source type: conference paper
- Publication: *Proceedings of EMNLP 2023*, pages 7312-7327

## Source Access
- Public source: [ACL Anthology page](https://aclanthology.org/2023.emnlp-main.453/)
- DOI / publisher: [ACL Anthology PDF landing page](https://aclanthology.org/2023.emnlp-main.453.pdf)
