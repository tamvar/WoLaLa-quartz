---
title: Source - How to Get Past Sesame Street
type: source
status: active
updated: 2026-07-29
ingestion_depth: brief
tags:
  - source
  - brief
  - pretraining
  - transfer
  - evaluation
  - bert
---

## Summary
Alex Wang, Jan Hula, Patrick Xia, Raghavendra Pappagari, R. Thomas McCoy, Roma Patel, Najoung Kim, Ian Tenney, Yinghui Huang, Katherin Yu, Shuning Jin, Berlin Chen, Benjamin Van Durme, Edouard Grave, Ellie Pavlick, and Samuel R. Bowman compare 19 sentence-level pretraining tasks as alternatives or complements to language modeling. Their main result is cautionary: language modeling remains a strong default, intermediate-task transfer is often unstable, and some apparently informative pretraining tasks help much less than hoped. For WoLaLa, the source matters because it treats pretraining choice as an empirical and methodological problem rather than as a simple more-data-is-better story.

## Strand Connections

- Primary: [[../overviews/Applications and Best Practices Overview|Applications and Best Practices]] (strand 6)
- Secondary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)

## WoLaLa Relevance
This source primarily supports [[../overviews/Applications and Best Practices Overview|Applications and Best Practices]] and secondarily [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]]. It is useful because it systematically compares pretraining objectives instead of assuming that any semantically flavored auxiliary task will improve transfer. For WoLaLa, that is a methodological reminder that competence evidence depends partly on the route by which a model was trained, and that pretraining alternatives can fail in revealing ways.

## Limitation Or Open Question
The paper predates the largest foundation-model regime and focuses on sentence encoders rather than full generative LLMs. The open question is how much its caution about intermediate-task transfer and random-baseline strength carries over to contemporary large-scale pretraining and instruction-tuning pipelines.

## Related Pages
- [[../overviews/Applications and Best Practices Overview|Applications and Best Practices Overview]]
- [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations Overview]]
- [[../sources/Source - T5|Source - T5]]
- [[../sources/Source - Deep Contextualized Word Representations|Source - Deep Contextualized Word Representations]]

## Source Identification
- Authors: Alex Wang, Jan Hula, Patrick Xia, Raghavendra Pappagari, R. Thomas McCoy, Roma Patel, Najoung Kim, Ian Tenney, Yinghui Huang, Katherin Yu, Shuning Jin, Berlin Chen, Benjamin Van Durme, Edouard Grave, Ellie Pavlick, and Samuel R. Bowman
- Title: *Can You Tell Me How to Get Past Sesame Street? Sentence-Level Pretraining Beyond Language Modeling*
- Year: 2019
- Source type: conference paper
- Publication: *Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics*

## Source Access
- Public source: [ACL Anthology page](https://aclanthology.org/P19-1439/)
- DOI / publisher: [arXiv abstract page](https://arxiv.org/abs/1812.10860)
