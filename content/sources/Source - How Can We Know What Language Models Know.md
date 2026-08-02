---
title: Source - How Can We Know What Language Models Know
type: source
status: active
updated: 2026-07-28
ingestion_depth: brief
tags:
  - source
  - brief
  - prompting
  - evaluation
  - knowledge-probing
  - lama
---

## Summary
Zhengbao Jiang, Frank Xu, Jun Araki, and Graham Neubig argue that prompt-based factual probing gives only a lower bound on what masked language models know, because poor prompts can fail to elicit information that is in fact encoded. They therefore propose automatic prompt discovery and ensembling methods that substantially improve performance on LAMA-style knowledge retrieval. For WoLaLa, the paper matters because it turns a widely used evaluation tactic into a methodological question: probing results depend not only on model content but on the linking hypothesis between prompts and stored knowledge.

## Strand Connections

- Primary: [[../overviews/Applications and Best Practices Overview|Applications and Best Practices]] (strand 6)
- Secondary: [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering]] (strand 7)

## WoLaLa Relevance
This source is important because it cautions against naive readings of `the model knows X` or `the model does not know X`. Prompting is part of the measurement instrument, not a transparent window into latent knowledge. That makes the paper useful whenever WoLaLa compares competence claims across different elicitation setups.

## Key Points
- Manually written prompts are only one possible way to query a language model's knowledge.
- Better prompts can substantially raise retrieval accuracy, tightening the lower bound on what the model encodes.
- Prompt mining, paraphrasing, and ensembling improve factual probing on LAMA.
- The paper shows that evaluation conclusions depend on the prompt-model interface, not just on the model.

## Limitation Or Open Question
Improved retrieval does not eliminate the deeper interpretive problem. Even if a prompt elicits the right answer, it remains open what sort of knowledge, representation, or mechanism supports that success.

## Related Pages
- [[../overviews/Applications and Best Practices Overview|Applications and Best Practices Overview]]
- [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering Overview]]
- [[../sources/Source - Analysis Methods in Neural Language Processing|Source - Analysis Methods in Neural Language Processing]]
- [[../sources/Source - Language Models Mostly Know What They Know|Source - Language Models Mostly Know What They Know]]

## Source Identification
- Authors: Zhengbao Jiang, Frank F. Xu, Jun Araki, and Graham Neubig
- Title: "How Can We Know What Language Models Know?"
- Year: 2020
- Source type: journal article
- Publication: *Transactions of the Association for Computational Linguistics* 8, 423-438

## Source Access
- Public source: [ACL Anthology page](https://aclanthology.org/2020.tacl-1.28/)
- DOI / publisher: [DOI landing page](https://doi.org/10.1162/tacl_a_00324)
